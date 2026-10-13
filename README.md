# Gravity for Mac

Gravity turns PDFs and images into text on your Mac. Your documents are not
uploaded. Review the result beside the original, then copy it or export it as
Markdown. Tables stay tables, and equations come out as LaTeX.

**Website:** https://gravityocr.trillionlabs.co

## Download

Get the latest version from the [website](https://gravityocr.trillionlabs.co)
or from [Releases](https://github.com/trillion-labs/GravityOCR-macOS/releases).
Open the DMG and drag Gravity to Applications.

**Requirements**

- A Mac with Apple Silicon (M1 or later)
- macOS 14 Sonoma or later
- An internet connection the first time you open Gravity

## First launch

The first time you open Gravity, it downloads its recognition model (about
2.2 GB) from Hugging Face. After that, recognition runs offline. The app itself
is about 420 MB.

Gravity opens PDF, PNG, JPEG, HEIC, and TIFF files.

## Report a problem or suggest an idea

Use [Issues](https://github.com/trillion-labs/GravityOCR-macOS/issues/new/choose):

- **Bug report:** something doesn't work or looks wrong.
- **Feature request:** something you'd like Gravity to do.

Before you open a new issue, search the existing issues to see if someone has
already reported it. Issues are public. Don't attach documents that contain
personal or confidential information.

When reporting a bug, it helps to include:

- your Gravity version (**Gravity ▸ About Gravity**)
- your macOS version and Mac model
- the steps that cause the problem
- the log at `~/Library/Logs/Gravity/backend.log`, if Gravity failed to start
  or stopped during recognition

## Remove Gravity

Choose **Gravity ▸ Storage…** to see what Gravity keeps on your Mac and to
remove all of it, including the downloaded model. Then move Gravity to the
Trash.

## The model

Gravity uses [GravityOCR-KO](https://huggingface.co/trillionlabs/GravityOCR-KO),
a version of [GravityOCR](https://huggingface.co/trillionlabs/GravityOCR)
further trained on Korean documents. The model code is at
[trillion-labs/GravityOCR](https://github.com/trillion-labs/GravityOCR), and the
technical report is [arXiv:2609.26638](https://arxiv.org/abs/2609.26638).

## Privacy and terms

- [Privacy notice](https://gravityocr.trillionlabs.co/privacy.html)
- [Terms](https://gravityocr.trillionlabs.co/terms.html)
- [Third-party notices](https://gravityocr.trillionlabs.co/third-party.html)

Gravity is made by [Trillion Labs](https://trillionlabs.co).

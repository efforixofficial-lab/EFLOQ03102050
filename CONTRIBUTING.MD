# Contributing to HPLOQ1148-2002

Thank you for helping build this project. Everyone is welcome, whether you write code, fix docs, add languages, or report bugs.

## Ways to contribute

- Report bugs and suggest features through Issues
- Improve documentation and translations
- Add or improve **language support**
- Build **extensions** (see below)
- Write tests
- Review pull requests

## Getting started

1. **Fork** the repository.
2. **Clone** your fork:
   ```bash
   git clone https://github.com/<your-username>/EFLOQ03102050.git
   cd EFLOQ03102050
   ```
3. **Create a branch**:
   ```bash
   git checkout -b feature/short-description
   ```
4. Make your changes and **test** them.
5. **Commit** with a clear message:
   ```bash
   git commit -m "Add: Tamil language support for call flow"
   ```
6. **Push** and open a **Pull Request**.

## Building an extension

Extensions let you add features without touching the core.

1. Copy the empty template: `extensions/_template/`
2. Rename the folder to your extension name, for example `extensions/crm_sync/`
3. Edit the files inside:
   ```
   extensions/crm_sync/
   ├── extension.json     # name, version, description, author
   ├── main.py            # your logic
   └── README.md          # how to use it
   ```
4. Add tests and mention the extension in your pull request.

## Pull request checklist

- [ ] The change is focused and does one thing
- [ ] Code is tested
- [ ] Documentation is updated
- [ ] No API keys, passwords, or customer data are included
- [ ] The change follows the Responsible Use rules below

## Code style

- Keep code simple and readable
- Add comments where logic is not obvious
- Use clear names for files, functions, and variables

## Responsible use rules

Because this project can collect leads and place calls, contributions must **not**:

- Bypass consent, do-not-call lists, or privacy laws
- Hide that a caller is an AI where disclosure is required
- Scrape or store personal data without a lawful basis
- Enable spam, scams, or harassment

Pull requests that break these rules will be rejected.

## Reporting bugs

Open an issue with:

- What you expected to happen
- What actually happened
- Steps to reproduce
- Your environment (OS, version, language)

## Security issues

Do **not** post security problems publicly. Contact the maintainers privately at `<security email>`.

## Code of Conduct

Be respectful and kind. Harassment and discrimination are not tolerated.

## License

By contributing, you agree that your contributions will be licensed under the project's license.

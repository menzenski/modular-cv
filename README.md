# modular-cv
Modular curriculum vitae in LaTeX which allows for easy generation of different CVs for different audiences.

## License

This CV style was first written by [Cies Breijs][cies] and released under [The MIT License][MIT], and then later modified by Vel of [LaTeX Templates][latex] and shared under a (sadly more restrictive) [Creative Commons CC-BY-NC-SA 3.0 License][cc]. My own fork is released under the same CC-BY-NC-SA 3.0 license.

## Usage

* This CV uses the `etaremune` package (available from [CTAN][ctan])
  to number items in an enumerated list in reverse order. You'll need
  to typeset it twice to produce the correct output. (If you typeset
  it once, enumerated lists won't be in reverse order.)

* Sections are incorporated into the main file through`\input{}`
  commands. Simply comment out the sections you want to exclude by
  prefacing those lines with the `%` character.

[cies]: https://github.com/cies/resume
[MIT]: http://opensource.org/licenses/MIT
[latex]: http://www.latextemplates.com/template/cies-resume-cv
[cc]: http://creativecommons.org/licenses/by-nc-sa/3.0/)
[ctan]: http://www.ctan.org/pkg/etaremune

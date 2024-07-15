## Add it to terminal .zshrc
```sh
alias cpp_run='function _cpp_run() { g++ -o "${1%.*}" "$1" && ./"${1%.*}" < input.txt > output.txt && rm "${1%.*}"; }; _cpp_run'
```

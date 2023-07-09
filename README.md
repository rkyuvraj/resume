This is my resume repo. Forked from [Sourabh](https://github.com/sb2nov/resume)

### Build using Docker

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex "\\def\\mobile{+91 1234567890}\\def\\email{user@gmail.com}\\include{yuvaraj-ravichandran}" yuvaraj-ravichandran.tex
```

### License

Format is MIT but all the data is owned by Sourabh Bajaj.

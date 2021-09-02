# Paperwork

Template for IEEE file stolen from [miki725/md2pdf-ieee-sample](https://github.com/miki725/md2pdf-ieee-sample) repository.

To generate the PDF, you may want to install the [task](https://taskfile.dev) and have a docker installed.

To generate pdf, run the following command:
```bash
task ieee -- <md file name without extension>
```

It will take the markdown file and generate a pdf file with the same name.

To see the full command, open the [Taskfile](./Taskfile.yml)

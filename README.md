# Resume Generator

This repository generates a `Resume.pdf` from a `Resume.tex` file using `pdflatex` with every commit.

## How it Works

1. **Edit the `Resume.tex` file:** Make changes to your resume in the `Resume.tex` file.
2. **Commit the changes:** Every commit will trigger the generation of the `Resume.pdf` file.
3. **Download the PDF:** The generated `Resume.pdf` will be available in the repository.

## Prerequisites

- Make sure you have `pdflatex` installed on your system.

## Usage

1. Clone the repository:
    ```sh
    git clone https://github.com/jackwaghan/Resume.git
    ```
2. Navigate to the repository directory:
    ```sh
    cd Resume
    ```
3. Edit the `Resume.tex` file with your preferred LaTeX editor.
4. Commit your changes:
    ```sh
    git add Resume.tex
    git commit -m "Update resume"
    git push origin main
    ```
5. The `Resume.pdf` will be generated automatically.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests.

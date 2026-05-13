# Public Downloads

This repository stores public downloadable files published by Gymnázium Zlín - Lesní čtvrť.

The repository is intended mainly for release assets, such as compiled ZIP packages of educational software, student programming projects, teacher-prepared applications, and other files linked from school-related websites.

## Purpose

This repository is used as a stable download location for files that should not be committed directly into website repositories.

Typical use cases:

- ZIP packages of student C# / WinForms projects
- teacher-prepared application releases
- public supporting files for lessons or projects
- larger downloadable files linked from GitHub Pages websites

## Student Projects

Student applications may be published here as compiled ZIP packages.

Student source code is not published in this repository.

Each ZIP package should contain only the files needed to run the application, for example:

- executable file
- required DLL files
- configuration files
- assets required by the application
- short README or run instructions, if useful

## Releases

Downloadable files should be uploaded as GitHub Release assets, not committed directly into the repository file tree.

Recommended release naming:
```text
proj-2026
proj-2027
teacher-tools-2026
```

Example release asset name:
```text
milan-novak-battleships.zip
```

Example public download URL:
```text
https://github.com/gymzl/public-downloads/releases/download/proj-2026/milan-novak-battleships.zip
```

## File Naming

Use lowercase ASCII file names when possible.

Recommended format:
```text
student-name-project-name.zip
```

## License and Use

Unless explicitly stated otherwise, files published in this repository are provided for educational and demonstration purposes by Gymnázium Zlín - Lesní čtvrť.

No permission is granted to redistribute, modify, or reuse the files outside their intended educational context.

Individual release assets may include their own license or usage notes.

## Publishing Checklist

Before publishing, check that the package does not contain:

- source code that should remain private
- personal data
- passwords, tokens, or secrets
- grading notes or internal comments
- files that cannot be publicly redistributed

# Harmonica

A web based 10 hole harmonica simulator in vanilla HTML,CSS,JS using the Web Audio API to play all the notes

## Features

- 10+10 hole layout
- Separate hole rows for Blowing/sucking the air
- No external libraries

## Notes

### Suck Air

| Hole | Note | Frequency |
| ---- | ---- | --------- |
| 1    | D4   | 293.66    |
| 2    | G4   | 392.00    |
| 3    | B4   | 493.88    |
| 4    | D5   | 587.33    |
| 5    | F5   | 698.46    |
| 6    | A5   | 880.00    |
| 7    | B5   | 987.77    |
| 8    | D6   | 1174.66   |
| 9    | F6   | 1396.91   |
| 10   | A6   | 1760.00   |

### Blow Air

| Hole | Note | Frequency |
| ---- | ---- | --------- |
| 1    | C4   | 261.63    |
| 2    | E4   | 329.63    |
| 3    | G4   | 392.00    |
| 4    | C5   | 523.25    |
| 5    | E5   | 659.25    |
| 6    | G5   | 783.99    |
| 7    | C6   | 1046.50   |
| 8    | E6   | 1318.51   |
| 9    | G6   | 1567.98   |
| 10   | C7   | 2093.00   |

## Ruining the Project

open the `dist/index.html` or `src/index.html` file in any browser

or

paste the content of `dist/uri.txt` into your browser URL

## Project Structure

```text
.
├── build.mjs
├── dist
│   ├── index.html
│   └── uri.txt
├── package-lock.json
├── package.json
├── README.md
└── src
    └── index.html
```

## Author

Created by [ApishRana](https://github.com/ApishRana)

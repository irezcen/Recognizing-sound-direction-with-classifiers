
# Recognizing sound direction with classifiers
The goal of this project is to recognize direction of of sound using simple, optimized classifiers. Classifiers were trained on both: Recorded and generated files using hrtfs in .sofa format. We couldn't achieve our goals, from recorded files we got about 40% accuracy score, and from generated about 90%.




## Run Locally

Clone the project

```bash
  git clone https://github.com/irezcen/Recognizing-sound-direction-with-classifiers
```
From database
https://team.inria.fr/perception/the-camil-dataset/#version11
download sound1_tiltLOW, sound1_tiltMID, sound1_tiltHIGH directories and puth them in 'dane_wav/' directory (create one) inside a main project directory. Unzip files, then put all data from 'sound1_tiltMID/Recorded' and 'sound1_tiltHIGH/Recorded' into 'sound1_tiltLOW/Recorded'.


## Authors

- [@irezcen](https://www.github.com/irezcen)
- [@komar6152](https://www.github.com/komar6152)


## License

MIT License

Copyright (c) 2023 Jakub Bociek

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.



## Dependencies

- [HRTF database](https://sofacoustics.org/data/database/aachen/)
- [Binaural cues](https://github.com/bingo-todd/Bianural-cues)
- [Recordings database](https://team.inria.fr/perception/the-camil-dataset/)


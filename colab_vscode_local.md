# ๐บColab + VSCode

Colab์ GPU๋ฅผ VSCode์์ ์ฌ์ฉํ๋ ๋ฐฉ๋ฒ์ 2๊ฐ์ง๊ฐ ์กด์ฌํฉ๋๋ค.

1. Colab์์ VSCode๋ฅผ ์ฐ๊ฒฐํด website์์ ์ฌ์ฉ
2. Local์ SSH๋ก Colab์ ์ ๊ทผํด์ ์ฌ์ฉ

์ฌ๊ฒฌ์ ๋ํ์๋ฉด, ๋ฐฉ๋ฒ 1์ ๊ฒฝ์ฐ๋ colab์์ ๋งค์ง ์ปค๋งจ๋ ์ฌ์ฉ์ผ๋ก ๋ค๋ฅธ ์ธ์ด๋ฅผ ์ฌ์ฉํ๋ ๊ฒ๊ณผ์ ์ฐจ๋ณ์ ์ ๋ชป ์ฐพ์์ต๋๋ค. ๊ตฌ๊ธ cloud ๊ด๋ จ article์ ๋ณด๋, ์๋ docker๋ ์ง์์ด ์๋๋ค๋ ์๊ธฐ๊ฐ ์๋๋ฐ  cloud์์ kubernetes๋ ์๋น์คํ๊ธฐ ๋๋ฌธ์(ํด๋ผ์ฐ๋ ์ชฝ์ ์ทจ์ฝ ๋ถ์ผ๋ผ ์์ธํ๋ ๋ชจ๋ฆ) ์ฌ์ฉ์์ ๋ฅ๋ ฅ์น์ ๋ฐ๋ผ์ ๊ตณ์ด 1๋ฒ ๋ฐฉ๋ฒ์ด ํ์ํ๊ฐ ํ๋ ์๊ฐ์ด ๋ญ๋๋ค.

[https://research.google.com/colaboratory/local-runtimes.html](https://research.google.com/colaboratory/local-runtimes.html)

๋ญ๊ฐ ๋ ๋์ ์ ํ์ธ์ง, ๋ณด์์ ์ด๋ป๊ฒ ๊ด๋ฆฌํด์ผํ๋์ง, mac์ด๋ linux, windows ์ด์์ฒด์  ๋ณ๋ก ๋ฐ์ํ  ์ ์๋ ์ด์ ์ปจํธ๋กค์ ์ด๋ป๊ฒ ํด์ผํ๋์ง์ ๋ํด์๋ ์์ง ์๋ฌธ์ด ๋ง์ง๋ง,,, ์ฐ์  ๊ฐ์์ ํ๊ฒฝ์ ๋ง๊ฒ ์๋ํด๋ณด๊ณ  ์ถ์ ๋ถ์ ์ํด ์ฐธ๊ณ ํ  ๋งํฌ๋ฅผ ๋จ๊น๋๋ค.

### references option 1

[https://amitness.com/vscode-on-colab/](https://amitness.com/vscode-on-colab/)

[How to Use Google Colab with VS Code](https://www.freecodecamp.org/news/how-to-use-google-colab-with-vs-code/)

### references option 2

ํ๊ธ๋ก ๋ ์ค๋ช์ ๋งจ ์์ ๋งํฌ์ด๊ณ , ๊ฐ์ธ์ ์ผ๋ก ์ถ์ฒ๋๋ฆฌ๊ณ  ์ถ์ url์ ๋งจ ๋ง์ง๋ง์๋๋ค. ์ด์ ๊ด๋ จ ๋งํฌ๋ ์ฐ๊ฒฐ ์ดํ์ ๋ํ ์ค๋ช๋ ์๊ธฐ ๋๋ฌธ์๋๋ค.

[https://tyeolrik.github.io/vscode/2020/08/13/vscode-1-how-to-remote-google-colab-with-your-visual-studio-code.html](https://tyeolrik.github.io/vscode/2020/08/13/vscode-1-how-to-remote-google-colab-with-your-visual-studio-code.html)

[Connect to VM through SSH (Google Colab and PuTTY)](https://unix.stackexchange.com/questions/478544/connect-to-vm-through-ssh-google-colab-and-putty)

[How to SSH into Google Colab? and run scripts from Terminal instead of Jupyter Notebook?](https://medium.com/@meet-minimalist/how-to-ssh-into-google-colab-and-run-scripts-from-terminal-instead-of-jupyter-notebook-3931f2674258)

### Notes

์ด์๋ github์์ ์ฐพ๋ ๊ฒฝ์ฐ๋ ์๊ณ , stackoverflow์ ๊ฒ์ํ๋ ๊ฒฝ์ฐ๋ ์์ด์, ์ ๊ฐ ์งํํ๋ฉด์ ์ฐพ์๋ ๋ํ์ ์ธ ์ฌ๋ก๋ ์๋์ ์ฒจ๋ถํ๊ฒ ์ต๋๋ค.

[Is it possible to connect vscode (on a local machine) with Google Colab (the free service) runtime?](https://stackoverflow.com/questions/59508225/is-it-possible-to-connect-vscode-on-a-local-machine-with-google-colab-the-fre/59537334#59537334)

[SSH into google colab](https://gist.github.com/yashkumaratri/204755a85977586cebbb58dc971496da#file-google-colab-ssh)

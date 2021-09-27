# 😺Colab + VSCode

Colab의 GPU를 VSCode에서 사용하는 방법은 2가지가 존재합니다.

1. Colab에서 VSCode를 연결해 website에서 사용
2. Local에 SSH로 Colab에 접근해서 사용

사견을 더하자면, 방법 1의 경우는 colab에서 매직 커맨드 사용으로 다른 언어를 사용하는 것과의 차별점을 못 찾았습니다. 구글 cloud 관련 article을 보니, 원래 docker는 지원이 안된다는 얘기가 있던데  cloud에서 kubernetes도 서비스하기 때문에(클라우드 쪽은 취약 분야라 자세히는 모름) 사용자의 능력치에 따라서 굳이 1번 방법이 필요한가 하는 생각이 듭니다.

[https://research.google.com/colaboratory/local-runtimes.html](https://research.google.com/colaboratory/local-runtimes.html)

뭐가 더 나은 선택인지, 보안은 어떻게 관리해야하는지, mac이나 linux, windows 운영체제 별로 발생할 수 있는 이슈 컨트롤을 어떻게 해야하는지에 대해서는 아직 의문이 많지만,,, 우선 각자의 환경에 맞게 시도해보고 싶을 분을 위해 참고할 링크를 남깁니다.

### references option 1

[https://amitness.com/vscode-on-colab/](https://amitness.com/vscode-on-colab/)

[How to Use Google Colab with VS Code](https://www.freecodecamp.org/news/how-to-use-google-colab-with-vs-code/)

### references option 2

한글로 된 설명은 맨 위의 링크이고, 개인적으로 추천드리고 싶은 url은 맨 마지막입니다. 이슈 관련 링크나 연결 이후에 대한 설명도 있기 때문입니다.

[https://tyeolrik.github.io/vscode/2020/08/13/vscode-1-how-to-remote-google-colab-with-your-visual-studio-code.html](https://tyeolrik.github.io/vscode/2020/08/13/vscode-1-how-to-remote-google-colab-with-your-visual-studio-code.html)

[Connect to VM through SSH (Google Colab and PuTTY)](https://unix.stackexchange.com/questions/478544/connect-to-vm-through-ssh-google-colab-and-putty)

[How to SSH into Google Colab? and run scripts from Terminal instead of Jupyter Notebook?](https://medium.com/@meet-minimalist/how-to-ssh-into-google-colab-and-run-scripts-from-terminal-instead-of-jupyter-notebook-3931f2674258)

### Notes

이슈는 github에서 찾는 경우도 있고, stackoverflow에 검색하는 경우도 있어서, 제가 진행하면서 찾았던 대표적인 사례도 아래에 첨부하겠습니다.

[Is it possible to connect vscode (on a local machine) with Google Colab (the free service) runtime?](https://stackoverflow.com/questions/59508225/is-it-possible-to-connect-vscode-on-a-local-machine-with-google-colab-the-fre/59537334#59537334)

[SSH into google colab](https://gist.github.com/yashkumaratri/204755a85977586cebbb58dc971496da#file-google-colab-ssh)

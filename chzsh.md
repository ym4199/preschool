# ZSH 

## 설치
zsh의 설치를 위해
>
>
	brew install zsh zsh-completions
	curl -L http://install.ohmyz.sh | sh
	chsh -s `which zsh`
	
> 	 echo $SHELL 을 통해 현재 shell 을 알 수 있다.

## Theme 설정
oh my zsh 의 theme를 변경할 수 있다.
> vim ~/.zshrc 을 이용하여
> 상단의 ZSH_THEME="robbyrussell" 항목을
> ZSH_THEME="agnoster" 로 변경
> 
> *여기까지 진행하면 터미널이 변경이 되긴 했는데 가독성 및 이용 환경의 개선이 되어보이진 않는다.* 

## iTerm2 테마
[iTerm2](http://iterm2colorschemes.com) 이곳에서 iTerm Themes를 받을 수 있다.

>cmd + , 터미널의 설정을 여는 단축키

상단 Profiles 탭을 선택 후 하단의 설정을 통해 Import 를 선택.
iTerm2에서 받은 파일의 하단 파일에 terminal-solarized dark를 선택.

이후 터미널을 종류하고 다시 켜보면 깔끔하게 바뀐 것을 확인 할 수 있다.  

이때 폰트가 ?로 표시된다면 폰트를 설정해줘야 한다.
>cmd + ,

동일한 탭에서 Font - Change 를 이용한다.
Meslo LG L DZ for Powerline 을 선택하자.

>echo "\ue0b0 \u00b1 \ue0a0 \u27a6 \u2718 \u26a1 \u2699"

이를 입력하여 ? 표시가 없이 잘 나오면 설정이 끝이난다.
## Pyenv

***Install Pyenv***

  **Ubuntu**
 --

       sudo apt-get install -y build-essential libssl-dev zlib1g-dev libbz2-dev \ libreadline-dev libsqlite3-dev wget curl llvm libncurses5-dev libncursesw5-dev \ xz-utils tk-dev libffi-dev liblzma-dev python-openssl git curl https://pyenv.run | bash


**Pyenv Virtualenv Install**

    git clone https://github.com/pyenv/pyenv-virtualenv.git $(pyenv root)/plugins/pyenv-virtualenv

**Bash**

    export PATH="$HOME/.pyenv/bin:$PATH"
    eval "$(pyenv init --path)"
    eval "$(pyenv virtualenv-init -)"

    
**Source** 

    source ~/.bashrc

**Zsh**


    export PATH="$HOME/.pyenv/bin:$PATH"
    eval "$(pyenv init --path)"
    eval "$(pyenv virtualenv-init -)"


**Source** 

    source ~/.zshrc
    
 **ตรวจสอบว่า virtual environment**

    pyenv virtualenvs
   
*การใช้งาน pyenv แสดงรุ่นของ Python ที่สามารถติดตั้งได้*

    pyenv install --list


*ติดตั้งรุ่นของ Python*


    pyenv install 3.9.1

*แสดงรุ่นของ Python ที่ถูกติดตั้ง*

    pyenv versions

*เปลี่ยนรุ่นของ Python สำหรับ directory ปัจจุบัน*

    pyenv local 3.9.1

*เปลี่ยนรุ่นของ Python สำหรับ user ปัจจุบัน*

    pyenv global  3.9.1

*Create Local Version By Tag Name*

    pyenv virtualenv 3.8.10 helloworld

    pyenv local helloworld
    
*List Virtualenvsg Name*

    pyenv virtualenvs
    
*Check Version Virtualenvsg

    pyenv versions
    
*Delete Local Version Tag Name*

    pyenv virtualenv-delete helloworld

Delete Form Project

    rm .python-version

Uninstall 

    pyenv uninstall 3.11.5

	

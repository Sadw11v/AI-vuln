# AI-vuln
A remote code execution vulnerability in ChatGLM（Zhipu Qingyan） large model, which can execute commands on the server through client interaction

version:GLM-4

url:https://chatglm.cn/main/alltoolsdetail

code execution vulnerability:

1.whoami

<img width="482" alt="39436c11073b84211cdeced7e58e603" src="https://github.com/Sadw11v/AI-vuln/assets/130206491/8fde1dc2-de24-4c82-8c16-fe4a5b5330e8">


2.read "/etc/passwd"

![图片](https://github.com/Sadw11v/AI-vuln/assets/130206491/4e1c9897-7cd2-492c-ba26-4fba751bb9fc)


3.read "etc/profile"

<img width="542" alt="1716346027844" src="https://github.com/Sadw11v/AI-vuln/assets/130206491/19ae6185-026b-4ea4-be3e-4bc8bcec8e0a">


4.execute "ls -l"

<img width="486" alt="0dea6f2e7fc7daa0b5457376ea2081b" src="https://github.com/Sadw11v/AI-vuln/assets/130206491/ab8beb3d-059e-49c7-aace-20f23c25d7ab">


5.read hostname

<img width="442" alt="44c7fb588b6c6d65ee25f71829e7d83" src="https://github.com/Sadw11v/AI-vuln/assets/130206491/62142867-b3b9-4724-bc0b-23dfa21ecccb">


6.echo $PATH

![图片](https://github.com/Sadw11v/AI-vuln/assets/130206491/9e534616-43ed-425e-adc3-9ec4c38d0f51)

7.env

<img width="558" alt="1716343864741" src="https://github.com/Sadw11v/AI-vuln/assets/130206491/3db97776-192f-4b0f-b92c-fafa99202572">

8.find /-perm -4000type f

<img width="515" alt="1716344173908" src="https://github.com/Sadw11v/AI-vuln/assets/130206491/337ed454-f0c5-404a-83ff-917dbb9a3609">






# AI-vuln
A remote code execution vulnerability in ChatGLM（Zhipu Qingyan） large model, which can execute commands on the server through client interaction

version:GLM-4

url:https://chatglm.cn/main/alltoolsdetail

code execution vulnerability:

1.read "/etc/passwd"

![图片](https://github.com/Sadw11v/AI-vuln/assets/130206491/c0d74f93-6599-4a63-aef7-a561db3b3439)


2.read "etc/profile"

![图片](https://github.com/Sadw11v/AI-vuln/assets/130206491/4c61f1df-2f64-4770-864c-1f3dbbb14d1a)


2.execute "ls -l"

<img width="486" alt="0dea6f2e7fc7daa0b5457376ea2081b" src="https://github.com/Sadw11v/AI-vuln/assets/130206491/ab8beb3d-059e-49c7-aace-20f23c25d7ab">


3.read hostname

![Uploading 44c7fb588b6c6d65ee25f71829e7d83.png…]()


4.echo $PATH

![图片](https://github.com/Sadw11v/AI-vuln/assets/130206491/9e534616-43ed-425e-adc3-9ec4c38d0f51)

5.env

<img width="558" alt="1716343864741" src="https://github.com/Sadw11v/AI-vuln/assets/130206491/3db97776-192f-4b0f-b92c-fafa99202572">

6.find /-perm -4000type f

<img width="515" alt="1716344173908" src="https://github.com/Sadw11v/AI-vuln/assets/130206491/337ed454-f0c5-404a-83ff-917dbb9a3609">






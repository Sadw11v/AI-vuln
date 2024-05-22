# AI-vuln
A remote code execution vulnerability in ChatGLM（Zhipu Qingyan） large model, which can execute commands on the server through client interaction

version:GLM-4

url:https://chatglm.cn/main/alltoolsdetail

code execution vulnerability:

1.read "/etc/passwd"

<img width="500" alt="1716343067319" src="https://github.com/Sadw11v/AI-vuln/assets/130206491/04f841df-59a3-49db-9af4-c37e4f98c965">
<img width="471" alt="1716343291311" src="https://github.com/Sadw11v/AI-vuln/assets/130206491/6e441e62-b977-48d0-bfc7-f14bf77c98ad">

2.read "etc/profile"

![图片](https://github.com/Sadw11v/AI-vuln/assets/130206491/4c61f1df-2f64-4770-864c-1f3dbbb14d1a)


2.execute "ls -l"

<img width="508" alt="1716343331300" src="https://github.com/Sadw11v/AI-vuln/assets/130206491/c2f1fba2-86e0-4a22-97ea-1bb1bacf9f65">

3.read hostname

![图片](https://github.com/Sadw11v/AI-vuln/assets/130206491/bcd61076-9f5b-4ae5-ab1a-759b91d6c7c7)

4.echo $PATH

![图片](https://github.com/Sadw11v/AI-vuln/assets/130206491/9e534616-43ed-425e-adc3-9ec4c38d0f51)

5.env

<img width="558" alt="1716343864741" src="https://github.com/Sadw11v/AI-vuln/assets/130206491/3db97776-192f-4b0f-b92c-fafa99202572">

6.find /-perm -4000type f

<img width="515" alt="1716344173908" src="https://github.com/Sadw11v/AI-vuln/assets/130206491/337ed454-f0c5-404a-83ff-917dbb9a3609">





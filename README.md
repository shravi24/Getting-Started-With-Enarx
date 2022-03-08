![Enarx](https://thumbs.dreamstime.com/b/enchanting-old-fairytale-castle-top-hill-idyllic-landscape-d-render-177332674.jpg)

# Getting started with Enarx 
To get started in learning a new technology or a language is hard at first. I want to reduce this initial frustation and make the journey much more enjoyable. This repo contains the things that you will need in journey with Enarx.

---

<p align="center"><b>🌈 Excited ?</b><br>Let's get started </p>


---

## Contents
- [ Introduction to Enarx ]( https://github.com/shravi24/Getting-Started-With-Enarx/#introduction-to-enarx )
- [How it Works?](https://github.com/shravi24/Getting-Started-With-Enarx/#how-it-works)
- [Blog References](https://github.com/shravi24/Getting-Started-With-Enarx/#blog-references)
- [Youtube References](https://github.com/shravi24/Getting-Started-With-Enarx/#youtube-references)
- [Why to use Enarx ?](https://github.com/shravi24/Getting-Started-With-Enarx/#why-to-use-enarx)
- [What is WebAssembly ?](https://github.com/shravi24/Getting-Started-With-Enarx/#what-is-webassembly-)
- [What is TEE ?](https://github.com/shravi24/Getting-Started-With-Enarx/#what-is-tee-)
- [How you can contribute and collborate ?](https://github.com/shravi24/Getting-Started-With-Enarx/#how-you-can-contribute-and-collborate-)
- [ Demos ](https://github.com/shravi24/Getting-Started-With-Enarx/#demos-)


---

### Introduction to Enarx
Enarx is an open source project which makes possible to deploy sensitive workloads on not fully trusted hosts in public cloud, private cloud , Edge, IoT  etc. It is a project that aims to reduce the number trust realtionships while maintaining a high level of security. 



### How it Works?

When learning about working of Enarx, you will definitely come across these two keywords the most: TEE (Trusted Execution Environment) and WASM (WebAssembly). {More about this in a bit..}

Enarx uses TEE(Trusted Execution Environments) to deploy into confidentiality and integrity protected WebAssembly runtimes. In simpler words, Enarx helps to run applications in a secure environment using TEE and WebAssembly runtimes.

In a more technical sense, Enarx is a deployment framework means it helps you deploy applications easily. First, You develop an application in language of your liking and then compile it to WebAssembly. Since Enarx has no stringent prerequisites like cloud or cpu vendors, you can run it on any cloud you like. So, regardless of the setup, you're ready to deploy your application in a secure environment.

If you are already feeling curious, feel free to check out the blogs and conference videos mentioned down below. 
Don't fret if you can't understand some of the terms in these blogs or videos. Don't worry, you will get there ;)

---
### Blog References 
- [Why to use Enarx ?](https://next.redhat.com/2019/08/16/trust-no-one-run-everywhere-introducing-enarx/)
- [Overview of Enarx](https://shravi24blogs.wordpress.com/2021/12/11/overview-of-enarx/)
- [How Enarx works ?](https://shravi24blogs.wordpress.com/2021/12/13/how-enarx-works/)
---

### Youtube References

- [Security and isolation](https://youtu.be/ajYWSAwIyPs?list=PLcApgpIcYo8kgPVO0rdvgQu3wJVTLe_LQ&t=96)
- [Enarx Overview](https://www.youtube.com/watch?v=kheJFhljEck)
- [Enarx Attestation](https://youtu.be/0MPCT2ocFIo?t=2058)
- [Protection for data in use](https://www.youtube.com/watch?v=JD70E7HHjlc)
- [WebAssembly + Confidential Computing by Nick Vidal](https://fosdem.org/2022/schedule/event/tee_enarx/)
- [Enarx Demo by Mike and Nathaneil](https://youtu.be/y_eDNTIkBBE?list=PLcApgpIcYo8kgPVO0rdvgQu3wJVTLe_LQ&t=774)
- [From Zero to Hero: Making Confidential Computing Accessible by Nick Vidal](https://www.youtube.com/watch?v=9GEZ1pnGN0I)
- [Understanding trust relationships for Confidential Computing by Mike Bursell ](https://www.youtube.com/watch?v=pLIAFCLNre4)

---

Let's get to the crux of matter. You might be wondering that if there are TEEs (Trusted Execution Environments) out there, so why use Enarx? In this section, we will briefly see why to use Enarx. 

---

### Why to use Enarx?

When you operate your workloads as VMs, in a serverless environment, or in the cloud, these workloads are susceptible to cloud providers, as well as anyone with access to the hypervisor, root, or kernel.
So basically you are trusting a lot of people who you don't know in order to run applications on cloud.
To provide a trusted environment for execution, the TEEs are built. But they have lot of inadequencies and are not easily used across platforms.

So, Enarx enables you to deploy your application in a secure environment without having to trust a large number of dependencies or rebuild your application for different platforms making it easier, faster and more secure to develop on.

If you are feeling curious about this, check the below mentioned article.

Check this out for more details :
[Trust No One, Run Everywhere–Introducing Enarx](https://next.redhat.com/2019/08/16/trust-no-one-run-everywhere-introducing-enarx/)

Let's now understand a few key terms that you would need throughout your contribution and learning journey in Enarx.


---

### What is WebAssembly ?

WebAssembly is a sort of binary-code that can be run in modern web browsers. It allows us to write code in different languages and run it on the web.

Here is a checklist to help you better understand WebAssembly :
- [What is WebAssembly and How it works](https://github.com/enarx/outreachy/tree/main/shravi24/Introduction%20to%20WebAssembly)
- [WebAssembly Guide](https://enarx.dev/docs/WebAssembly/Introduction)
- [Different WebAssembly Runtimes](https://github.com/appcypher/awesome-wasm-runtimes)
- Check out the [Demos](https://github.com/enarx/outreachy) implemented by Outreachy Contributors.

---

### What is TEE ?
A Trusted Execution Environment (TEE) is a an environment in which the code that is run and the data that is accessible are physically segregated and confidentially secured, ensuring that no one with a lack of integrity may access the data or alter the code or its behaviour.

Checkout for more :
[TEE](https://shravi24blogs.wordpress.com/2021/12/12/trusted-execution-environment-tee/)

---

###  How you can contribute and collborate ?

![adventure](https://thumbs.dreamstime.com/b/vector-vintage-card-forest-night-sky-inspirational-phrase-let-adventure-begin-stylish-hipster-background-motivational-68783071.jpg)
  
Best way to get better at something is by doing. Get together with the community, share your ideas and implement few projects. 

So how you can contribute and collborate ?

At first, you should get familiar with the community and ask questions if have any. Enarx has a great community and you will surely be at ease after the inital jitters. 

For joining the Chat check out the [Community chat](https://chat.enarx.dev/). 

If you have any questions, feel free to contact [Nick Vidal](https://twitter.com/nickvidal) and all the community members. They are some of the most amazing people I have ever met.

To get started in contribution, check out the below links.
  
[Contribution Guide](https://enarx.dev/docs/Contributing/Introduction)

[Enarx project repository](https://github.com/enarx/enarx)

You can start with [Good first issues](https://github.com/enarx/enarx/labels/good%20first%20issue) to get more familiar with the Enarx codebase.

For starting with the contributions, you may have to install Enarx on your local system. 
[Instructions to install the Enarx](https://enarx.dev/docs/Installation/Setup)

This may require [some additional hardware supports](https://enarx.dev/docs/Installation/Requirements) to be enabled. If you don't have the necessary hardware support then you can also access the lab machines to work on Enarx.
[Getting lab access to contribute to Enarx](https://enarx.dev/docs/Contributing/Lab)

You can check out the links down below to check out demos we created as Outreachy Interns. 

---

###  Demos : 

1. [ML Diabetes](https://github.com/jnyfah/Enarx-Demo)

2. [TCP MIO Server]()

3. [Bulletproof](https://github.com/shravi24/Enarx-Bulletproof-Demo)





I have added a few things here and if you think some other things that need to be here as well feel free to create an issue and reach out.




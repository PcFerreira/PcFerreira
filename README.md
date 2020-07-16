### PcFerreira@github:~$ kubectl apply -f profile.yml

```yaml
apiVersion: v1
kind: Developer
metadata:
  name: Pedro-deployment
  labels:
    tier: backend
spec:
  containers:
  - name: Pedro
    image: Pedro:latest
    env:
    - name: Code
      value: '[Javascript, PHP, TypeScript]'
    - name: Tools
      value: '[NodeJs, Docker, Kubernetes, Prometheus, OracleDB]'
    - name: Linkedin
      value: 'https://www.linkedin.com/in/pedrocesarf/' 
```


<!--
**PcFerreira/PcFerreira** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

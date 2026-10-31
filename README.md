<div align="center">

# Sistema Supervisório | Java & Arduino

### Interface supervisória Java Web integrada a hardware Arduino para estudo de monitoramento e acionamento de dispositivos.

[![GitHub](https://img.shields.io/badge/Ver_no_GitHub-181717?style=for-the-badge&logo=github)](https://github.com/KalleoLeandro/sistema-supervisorio-java)
![Documentação](https://img.shields.io/badge/Documentação-pt--BR-0F766E?style=for-the-badge)

![Java](https://img.shields.io/badge/Java-26364A?style=for-the-badge&logoColor=white) ![JSF](https://img.shields.io/badge/JSF-26364A?style=for-the-badge&logoColor=white) ![PrimeFaces](https://img.shields.io/badge/PrimeFaces-26364A?style=for-the-badge&logoColor=white) ![Arduino](https://img.shields.io/badge/Arduino-26364A?style=for-the-badge&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-26364A?style=for-the-badge&logoColor=white) ![Maven](https://img.shields.io/badge/Maven-26364A?style=for-the-badge&logoColor=white)

</div>

---

## ✨ Visão geral

Interface supervisória Java Web integrada a hardware Arduino para estudo de monitoramento e acionamento de dispositivos.

## 🚀 O que você encontra aqui

- **Interface Java Web com JSF e PrimeFaces**
- **Comunicação serial por jSerialComm**
- **Persistência em MySQL**
- **Diagrama físico da ligação com Arduino**

## 🧰 Tecnologias

`Java`, `JSF`, `PrimeFaces`, `Arduino`, `MySQL`, `Maven`.

## 🖼️ Visão técnica / demonstração

![Esquema de hardware](esquema.png)

## ▶️ Como explorar / executar

1. Importe o projeto Maven na IDE.
2. Importe `database/sistema_lampadas.sql` no MySQL.
3. Ajuste a configuração de banco/porta serial ao seu ambiente.
4. Faça a montagem de referência usando `esquema.png` e carregue `arduino/supervis_rio.ino` na placa.
5. Execute o WAR em um servidor compatível com Java EE/`javax.*`.

## 📁 Repositório

```bash
git clone https://github.com/KalleoLeandro/sistema-supervisorio-java.git
cd sistema-supervisorio-java
```

[Consultar os arquivos e o histórico do projeto](https://github.com/KalleoLeandro/sistema-supervisorio-java)

## 📝 Observações

> **Limitação conhecida:** a documentação original relata que a thread serial não reinicia corretamente após fechar a aplicação, sendo necessário reiniciar o Arduino e o servidor.

---

<div align="center">

Desenvolvido e mantido por [Kalleo Leandro](https://github.com/KalleoLeandro).

⭐ Se este projeto for útil, considere deixar uma estrela.

</div>

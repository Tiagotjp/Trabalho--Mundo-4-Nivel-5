# 🚀 Missão Prática | Nível 5 | Mundo 4 - Interligação IoT com a Nuvem 🌐



## 📌 Introdução

Bem-vindo(a) ao repositório da **Missão Prática - Nível 5**! Aqui, você aprenderá como interligar dispositivos IoT à nuvem usando o **Azure IoT Hub**. Esta prática é ideal para estudantes que desejam aprofundar seus conhecimentos em **Internet das Coisas (IoT)** e **computação em nuvem**. 🚀

---

## 🎯 Objetivos

- ✅ Criar um **Hub IoT** no Azure.
- ✅ Registrar dispositivos no **Hub IoT**.
- ✅ Utilizar a extensão **Hub IoT no VS Code**.
- ✅ Gerenciar e interagir com dispositivos IoT.
- ✅ Conectar um **simulador de Raspberry Pi** ao Hub IoT.
- ✅ Visualizar dados de sensores **em tempo real**.

---

## 🛠️ Tecnologias Utilizadas

- 🏢 **Microsoft Azure** - Para criar e gerenciar o IoT Hub.
- 💻 **Visual Studio Code** - Desenvolvimento e monitoramento.
- 🍓 **Raspberry Pi Azure IoT Simulator** - Simulação de dispositivos IoT.
- 🌐 **Node.js** - Para o aplicativo web de visualização de dados.
- 🔧 **CLI do Azure** - Gerenciamento do ambiente.

---

## 🚀 Como Configurar e Executar

### 📌 1. Criar um Hub IoT no Azure

```bash
1. Acesse o [Azure Portal](https://portal.azure.com/)
2. Crie um **recurso** > **Internet das Coisas** > **Hub IoT**
3. Escolha a camada "Gratuita" e finalize a criação
```

### 📌 2. Registrar um Dispositivo no Hub IoT

```bash
1. No menu do Hub IoT, selecione **Dispositivos**
2. Clique em **Adicionar Dispositivo** e forneça um nome
3. Copie a **cadeia de conexão primária**
```

### 📌 3. Conectar o Simulador de Raspberry Pi

```bash
1. Acesse o [Simulador Azure IoT](https://azure-samples.github.io/raspberry-pi-web-simulator/#GetStarted)
2. Substitua a cadeia de conexão na linha 15 do código
3. Clique em "Run" para iniciar a comunicação
```

### 📌 4. Monitoramento pelo Visual Studio Code

```bash
1. Instale a extensão "Azure IoT Hub" no VS Code
2. Expanda a seção "Hub IoT do Azure"
3. Selecione seu "Hub IoT" e visualize os dispositivos
```

### 📌 5. Visualizar Dados com um Aplicativo Web

```bash
git clone https://github.com/Azure-Samples/web-apps-node-iot-hub-data-visualization
cd web-apps-node-iot-hub-data-visualization
npm install
npm start
```

Acesse `http://localhost:3000` para visualizar os dados 📊

### 📌 6. Hospedar no Azure

```bash
# Criar um plano de serviço
az appservice plan create --name MEU_PLANO --resource-group MEU_GRUPO --sku FREE

# Criar o aplicativo web
az webapp create -n MEU_APP -g MEU_GRUPO -p MEU_PLANO --runtime "NODE:16LTS"

# Configurar variáveis de ambiente
az webapp config appsettings set -n MEU_APP -g MEU_GRUPO --settings IotHubConnectionString="MINHA_STRING" EventHubConsumerGroup="MEU_GRUPO_CONSUMIDOR"
```

Acesse `https://MEU_APP.azurewebsites.net` para visualizar os dados online. 🌍

---

## 📌 Entrega da Prática

- ✔ **Armazene o projeto no GitHub**.
- ✔ **Anexe a documentação do projeto no repositório**.
- ✔ **Compartilhe o link do repositório para avaliação**.

---

## 🎯 Resultados Esperados

- ✅ Gerenciamento de dispositivos IoT no Azure.
- ✅ Interação com o **Simulador Raspberry Pi**.
- ✅ Monitoramento de mensagens no VS Code.
- ✅ Visualização de dados **em tempo real**.

---

## 📬 Contato

📌 Para dúvidas e sugestões, abra uma **issue** ou envie um **pull request**.

🚀 **Desenvolvido para fins acadêmicos, explorando tecnologias IoT e nuvem!** 🌐

![Image](https://github.com/user-attachments/assets/310c4f5c-08f7-417d-b40c-28ebc9df8d91)

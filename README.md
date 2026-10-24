# 🛡️ No-Trace — Privacy & Security Utility

O **No-Trace** é um utilitário móvel focado em privacidade máxima, navegação limpa e proteção de dados do usuário no dispositivo. 

Projetado sob a filosofia de **Zero-Conhecimento (Zero-Knowledge)**, o No-Trace garante que suas sessões de navegação e preferências permaneçam estritamente privadas, apagando automaticamente qualquer rastro digital assim que o uso é encerrado.

---

## ✨ Funcionalidades Principais

* **🧹 Auto-Clear em Segundo Plano:** Limpeza automática de cache, cookies, armazenamento local (LocalStorage, WebSQL) e histórico de navegação sempre que o app é minimizado ou fechado.
* **🚨 Botão do Pânico (Quick Cover):** Encerra instantaneamente a sessão ativa, limpa a memória temporária do aplicativo e redireciona a tela para uma interface neutra com um único toque ou gesto.
* **🔒 Proteção de Tela e Multitarefa (`FLAG_SECURE`):** Impede capturas de tela (screenshots) no Android e aplica desfoque automático de tela (blur/overlay) na multitarefa do iOS.
* **🔑 Autenticação Biométrica (App Lock):** Suporte nativo a Face ID, Touch ID e impressão digital para desbloqueio e confirmação de ações sensíveis.
* **🌐 Escolha de DNS Seguro (DoH):** Suporte a protocolos de DNS encriptado para maior proteção no tráfego de rede.

---

## 🔒 Compromisso com a Privacidade

O No-Trace **não coleta, não armazena e não compartilha** nenhum tipo de dados pessoais ou histórico de navegação em servidores externos. 

Você pode acessar a **Política de Privacidade oficial** do projeto diretamente pelo link:
👉 [Política de Privacidade do No-Trace](index.html) *(ou insira a URL do seu GitHub Pages)*

---

## 🛠️ Tecnologias Utilizadas

* **Framework:** [Flutter](https://flutter.dev/) (Dart)
* **Web Engine:** `flutter_inappwebview`
* **Biometria:** `local_auth`
* **Monetização:** `google_mobile_ads` (exibição de anúncios restrita a telas de configurações neutras, em conformidade com as diretrizes do Google AdMob)

---

## 📲 Como Compilar e Rodar o Projeto

### Pré-requisitos
* Flutter SDK instalado e configurado
* Android Studio / Xcode configurados
* Conta de Desenvolvedor (Google Play Console / Apple Developer Program)

### Passos
1. Clone o repositório:
   ```bash
   git clone [https://github.com/seu-usuario/no-trace-privacy.git](https://github.com/seu-usuario/no-trace-privacy.git)

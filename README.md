
```markdown
# ✨ Flutter Login App 📱

Este projeto é uma aplicação **simples** em Flutter que implementa uma tela de login com navegação para uma página home. **Não há lógica de autenticação**, o foco aqui é testar a criação e navegação entre telas no Flutter.

## 🚀 Funcionalidades

- **🖥️ Tela de Login**: Campos para `Username` e `Password`, botão de "Forgot Password?" e "Login".
- **🔄 Navegação**: O botão "Login" leva o usuário para a tela home.
- **🏠 Tela Home**: Exibe um contador que incrementa toda vez que o botão de "+" (floating action button) é pressionado.

## 🛠️ Estrutura do Projeto

O projeto contém duas telas principais:

1. **Login** (`login.dart`)
    - Tela de login com campos de entrada.
    - Botão para navegar para a tela home.
    
2. **Home** (`home.dart`)
    - Tela que exibe um contador de cliques, incrementado ao pressionar o botão flutuante.

### 🧠 Arquitetura

- **StatelessWidget**: Utilizado na tela de `Login`, pois não há estado dinâmico.
- **StatefulWidget**: Usado na tela `Home` para controlar o contador de cliques.

## 🚫 Aviso Importante

🔒 **Esta aplicação não possui lógica de autenticação real**. Os campos de login são apenas visuais, e o botão de "Login" leva diretamente para a tela home. O objetivo principal deste projeto é **praticar a criação de interfaces** no Flutter.

## 🛠️ Tecnologias Utilizadas

- **Flutter**: Framework para desenvolvimento de apps multiplataforma (Android, iOS, Web).
- **Dart**: Linguagem de programação usada no Flutter.

## 🎮 Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-repositorio/flutter-login-app.git
   ```
   
2. Navegue até a pasta do projeto:
   ```bash
   cd flutter-login-app
   ```

3. Instale as dependências:
   ```bash
   flutter pub get
   ```

4. Execute o projeto:
   ```bash
   flutter run
   ```

## 📸 Capturas de Tela

### Tela de Login
![Login Screen](assets/login_screenshot.png)

### Tela Home
![Home Screen](assets/home_screenshot.png)

## 📂 Estrutura de Arquivos

```bash
lib/
├── home.dart        # Tela Home
└── login.dart       # Tela Login
```


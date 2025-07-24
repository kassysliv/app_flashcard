# 📚 FlashCards – 2ª VA

Aplicativo educacional interativo desenvolvido para a 2ª Verificação de Aprendizagem. Com ele, é possível estudar utilizando flashcards personalizados por matéria. O app incentiva o aprendizado dinâmico e organizado.

---

## ✅ Funcionalidades Implementadas

- ✅ Tela inicial com introdução  
- ✅ Tela de cadastro com validações (e-mail, senha, confirmação)  
- ✅ Cadastro de data de nascimento  
- ✅ Estudo com flashcards interativos (virar para ver a resposta)  
- ✅ Flashcards pré-carregados por disciplina (Português, Matemática, História, etc.)  
- ✅ Avanço de flashcards com botão "Próximo"  
- ✅ Adição de novas matérias com perguntas e respostas personalizadas  
- ✅ Visualização de todas as matérias cadastradas e seus flashcards  
- ✅ Navegação entre telas com transições suaves  
- ✅ Suporte a modo escuro com layout adaptado para celular  
- ✅ Armazenamento local básico com `JsonStore`  

---

## 🧰 Bibliotecas Utilizadas

- [Kivy](https://kivy.org/) – Framework de interfaces gráficas  
- [KivyMD](https://kivymd.readthedocs.io/) – Componentes Material Design para Kivy  
- [JsonStore (Kivy)](https://kivy.org/doc/stable/api-kivy.storage.jsonstore.html) – Armazenamento local simples  
- Widgets e layouts:  
  - `MDBoxLayout`, `MDLabel`, `MDTextField`, `MDRaisedButton`, `MDTopAppBar`, `MDCard`, `ScrollView`, `AnchorLayout`  

---

## 📸 Screenshots

### 🏠 Tela Inicial  
![Tela Inicial](screenshots/tela_inicial.png)

### 📝 Tela de Cadastro  
![Tela Cadastro](screenshots/tela_cadastro.png)

### 🎴 Tela de Estudo com Flashcard  
![Tela Flashcard](screenshots/tela_flashcard.png)

### ➕ Tela de Adicionar Matéria  
![Adicionar Matéria](screenshots/tela_adicionar_materia.png)

### 📂 Tela de Visualização de Matérias  
![Tela Matérias](screenshots/tela_materias.png)

> ⚠️ As imagens devem estar na pasta `screenshots/` na raiz do seu repositório para aparecerem corretamente.

---

## 🔗 Link do Projeto

[🔗 Clique aqui para acessar o repositório no GitHub](https://github.com/kassysliv/app_flashcard/commit/b1e8aec74b782ce58c0cd0d792a94a9fc8c7f868)

---

## 🧠 Detalhamento do Aplicativo e Validações

O **FlashCards App** é uma aplicação educacional pensada para facilitar o aprendizado através de cartões interativos de perguntas e respostas, permitindo que o aluno revise matérias de forma prática e divertida. A experiência do usuário é organizada, intuitiva e adaptada ao uso em dispositivos móveis.

### 📝 Cadastro e Campos de Entrada

Na primeira execução, o usuário deve preencher um pequeno formulário para começar a usar o app. Os campos são:

- **Data de nascimento**
- **E-mail**
- **Senha**
- **Confirmação da senha**

#### ✅ Validações automáticas:

- **E-mail**: Verificação se contém `@` e `.`, impedindo entrada de formatos inválidos.  
- **Senha**: Deve ter no mínimo 6 caracteres.  
- **Confirmação de senha**: Deve ser idêntica à senha anterior.  
- **Campos obrigatórios**: Se qualquer campo estiver em branco, o app alerta o usuário com mensagens claras e objetivas.

Essas validações garantem que o usuário tenha uma experiência segura, sem erros no preenchimento.

---

### 🎴 Estudo com Flashcards

Após o cadastro, o usuário pode estudar por meio de flashcards que mostram uma **pergunta** na frente e revelam a **resposta** ao toque. O botão **“Próximo”** permite seguir para o próximo cartão, promovendo revisão sequencial.

O app já vem com **25 questões distribuídas em 5 disciplinas**:

- Português  
- Matemática  
- História  
- Geografia  
- Ciências  

Os cartões são embaralhados e o estudo é contínuo.

---

### ➕ Cadastro de Matérias Personalizadas

O usuário também pode:

1. Criar novas matérias  
2. Inserir quantas perguntas e respostas quiser  
3. Salvar a matéria, que é adicionada à lista de estudo  

O app impede o cadastro de perguntas ou matérias vazias, garantindo organização e coerência nos dados salvos.

---

### 📂 Visualização e Gerenciamento

Na aba de visualização, o usuário encontra uma lista de todas as matérias personalizadas criadas. Cada matéria pode ser:

- Visualizada com todas as suas perguntas e respostas  
- Removida com um botão específico, que exclui seus dados da memória  

---

### 💾 Armazenamento e Lógica

O app usa `JsonStore` para armazenar dados simples, como saber se o usuário já se cadastrou. As matérias e flashcards são mantidos em listas e dicionários dentro da aplicação, permitindo um funcionamento leve e eficiente.

---

### ✨ Diferenciais

- Interface Material Design com KivyMD  
- Navegação por cartões com botões visuais  
- Validações em tempo real para evitar erros  
- Suporte a modo escuro  
- Organização intuitiva entre telas  
- Estudo dinâmico que respeita o ritmo do aluno  

---


# 🎓 FlashCards – Aplicativo Educacional | 2ªV.A

> Um app interativo para estudar com eficiência usando **flashcards personalizados por matéria**. Desenvolvido como parte da 2ª VA, este projeto alia tecnologia, design e educação para promover **aprendizado dinâmico, organizado e intuitivo**.

---

## 📱 Visão Geral

O **FlashCards App** é uma ferramenta educacional desenvolvida com **Kivy** e **KivyMD**, voltada para estudantes que desejam revisar conteúdos com praticidade. Ele oferece recursos como criação de matérias, estudo com cartões interativos e uma interface moderna adaptada para dispositivos móveis.. O FlashCards App oferece uma maneira divertida, moderna e eficiente de estudar por meio de cartões interativos, organizados por matérias. Com navegação intuitiva, validações inteligentes e uma interface responsiva.



---

## ✅ Funcionalidades

- 👋 Tela de **boas-vindas** com introdução  
- 📝 Tela de **cadastro** com validações completas  
- 🎂 Campo de **data de nascimento** com validação  
- 🎴 Estudo com **flashcards interativos** (toque para revelar a resposta)  
- 📚 **Flashcards pré-carregados** por disciplina (Português, Matemática, etc.)  
- ⏭️ Botão **“Próximo”** para avançar no estudo  
- ➕ Adição de **matérias personalizadas** com perguntas e respostas  
- 👁️ Visualização de todas as matérias cadastradas  
- 🔄 Navegação suave entre telas com transições animadas  
- 🌙 Suporte ao **modo escuro**  
- 💾 Armazenamento local com `JsonStore` para persistência dos dados  

---

## 🧠 Experiência do Usuário

### 📝 Cadastro com Validações

O app inicia com um formulário simples e validado:

| Campo                 | Validação                               |
|----------------------|------------------------------------------|
| 📧 E-mail            | Deve conter `@` e `.`                    |
| 🔑 Senha             | Mínimo de 6 caracteres                   |
| 🔁 Confirmação senha | Deve ser igual à senha                   |
| 📅 Data de nascimento| Deve conter `/` no formato (dd/mm/aaaa)  |
| 🚫 Campos vazios     | Exibem alertas claros e objetivos        |

---

### 🎴 Estudo com Flashcards

- Exibição de uma **pergunta na frente** e **resposta no verso**
- Botão **“Próximo”** para avançar na revisão
- Cartões embaralhados e sequenciais
- 25 questões iniciais em 5 disciplinas:
- obs: só coloquei essa quantidade para ficar harmônico 

| Disciplina     | Nº de Perguntas |
|----------------|-----------------|
| Português      | 5               |
| Matemática     | 5               |
| História       | 5               |
| Geografia      | 5               |
| Ciências       | 5               |

---

### ➕ Adicionar Matérias

Você pode:

1. Criar novas matérias com nome personalizado  
2. Adicionar diversas perguntas e respostas  
3. Salvar e começar a estudar imediatamente  

> 🛡️ O app bloqueia cadastros vazios para garantir integridade nos dados.

---

### 📂 Visualização e Gerenciamento

- Listagem de **todas as matérias** criadas  
- Opção de **visualizar perguntas e respostas**  
- Botão de **excluir matéria** com remoção direta dos dados  

---

## 💾 Armazenamento

Utiliza `JsonStore` do Kivy para:

- Verificar se o usuário já está cadastrado  
- Armazenar dados essenciais de maneira leve e eficiente  
- Manter dados enquanto o app estiver em uso (sem banco de dados externo)  

---

## 🧰 Tecnologias Utilizadas

| Tecnologia | Descrição |
|------------|-----------|
| [Kivy](https://kivy.org/) | Framework Python para interfaces gráficas multiplataforma |
| [KivyMD](https://kivymd.readthedocs.io/) | Componentes Material Design para Kivy |
| [JsonStore](https://kivy.org/doc/stable/api-kivy.storage.jsonstore.html) | Armazenamento local em JSON simples |
| Layouts e Widgets | `MDBoxLayout`, `MDCard`, `MDTopAppBar`, `MDLabel`, `MDTextField`, `ScrollView`, etc. |

---

## 📸 Imagens do App

### 🏠 Tela Inicial  
![Tela Inicial](https://github.com/kassysliv/app_flashcard/commit/6d65afb3e36e50daf14c7980338bfc8b5d7dc8dc)

### 📝 Tela de Cadastro  
![Tela Cadastro](https://github.com/kassysliv/app_flashcard/blob/INICIO_EM_HTML/dados%20do%20cadastro.png)

### 🎴 Estudo com Flashcards  
![Flashcards](https://github.com/kassysliv/app_flashcard/blob/INICIO_EM_HTML/tela%20das%20funcoes.png)  
![Flashcards 2](https://github.com/kassysliv/app_flashcard/blob/INICIO_EM_HTML/tela%20das%20funcoes%20(2).png)

### ➕ Adicionar Matéria  
![Adicionar 1](https://github.com/kassysliv/app_flashcard/blob/INICIO_EM_HTML/tela%20de%20adicionar%20materias.png)  
![Adicionar 2](https://github.com/kassysliv/app_flashcard/blob/INICIO_EM_HTML/tela%20de%20adicionar%20materia.png)

### 📂 Visualizar Matérias  
![Matérias](https://github.com/kassysliv/app_flashcard/blob/INICIO_EM_HTML/adicionar%20materia%20.png)  
![Matérias 2](https://github.com/kassysliv/app_flashcard/commit/350a9be4c3ef0c3f38ccba17c5796a8784c40ad5)



---

## 🔗 Repositório no GitHub

📎 [Acesse aqui o repositório completo](https://github.com/kassysliv/app_flashcard)

---

## ✨ Diferenciais do Projeto

- ✅ Interface moderna com **Material Design**
- ✅ Navegação fluida entre telas  
- ✅ Estudo dinâmico com flashcards clicáveis  
- ✅ Validações em tempo real para evitar erros de uso  
- ✅ Suporte ao **modo escuro**  
- ✅ Código bem organizado com separação de telas e lógica  

---🎓 Observações Finais

O FlashCards App foi desenvolvido com foco na experiência do usuário e na eficácia do estudo. Com validações cuidadosas, transições suaves e armazenamento simples, o aplicativo oferece uma solução prática para estudantes que desejam revisar conteúdos de forma divertida e personalizada.

Ideal para uso escolar, revisões rápidas ou como ferramenta de apoio ao ensino!




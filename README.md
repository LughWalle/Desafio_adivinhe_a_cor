# Desafio_adivinhe_a_cor
Projeto com objetivo de ver conceitos basicos de React: Criar um jogo onde o jogador deve adivinhar qual cor corresponde ao nome exibido na tela.

# Jogo de Adivinhação de Cores - React

![React](https://img.shields.io/badge/React-18.2.0-blue) ![License](https://img.shields.io/badge/License-MIT-green)

Jogo educacional em React onde o jogador deve adivinhar qual cor corresponde ao nome exibido.

![Demonstração](demo.gif)

---

## Descrição
Projeto desenvolvido para praticar conceitos básicos de React como:
- Componentes funcionais
- Hooks (`useState`)
- Eventos
- Estilização condicional
- Geração de dados aleatórios

---

## Funcionalidades Principais

### Requisitos Básicos
1. **Geração de Cores**
   - 3 cores aleatórias em hexadecimal (#RRGGBB)
   - 1 cor "correta" selecionada aleatoriamente

2. **Interface**
   - Título com nome da cor correta
   - 3 botões coloridos
   - Display de pontuação
   - Botão "Nova Partida"

3. **Interações**
   - Verificação de resposta
   - Feedback visual (acerto/erro)
   - Atualização automática de pontuação

4. **Reinicialização**
   - Reset de cores, pontuação e timer (se aplicável)

### Bônus (Opcional)
- Timer de 10 segundos por rodada
- Níveis de dificuldade (3/5/10 cores)
- Salvamento de recorde no `localStorage`
- Animações de feedback

---

## Instalação

1. **Criar projeto React:**
   ```bash
   npx create-react-app color-game
   # ou
   npm create vite@latest color-game -- --template react

2. **Estrutura inicial:**
   ```javascript
   // src/App.js
    import { useState } from "react";
    import "./App.css";
    
    function App() {
      return (
        <div className="App">
          <h1>Adivinhe a Cor</h1>
          {/* Seu código aqui */}
        </div>
      );
    }
    
    export default App;
3. **DependÊncias necessárias**
    -  React 18+
    -  Biblioteca de geração de cores (opcional)
  
## Como Jogar
  1. Observe o nome da cor exibido no título
  2. Clique no botão com a cor correspondente
  3. Receba feedback imediato:
    -  ✅ Verde: Acertou (+1 ponto)
    -  ❌ Vermelho: Errou
  4. Reinicie o jogo a qualquer momento

## Tecnologias Utilizadas
  -  React.js
  -  Hooks (useState)
  -  CSS Modules/Styled Components
  -  JavaScript ES6+
  -  HTML5


## Contribuição(como iniciar o projeto)
  1. Fork este repositório
  2. Crie uma branch (git checkout -b feature/nome)
  3. Commit suas mudanças (git commit -m 'Adiciona X')
  4. Push para a branch (git push origin feature/nome)
  5. Abra um Pull Request

## Licença
##### MIT License - veja o arquivo LICENSE para detalhes

**Autor**: LughWalle
**LinkedIn**: https://www.linkedin.com/in/lucivalfrancafilho/
**GitHub**: github.com/LughWalle

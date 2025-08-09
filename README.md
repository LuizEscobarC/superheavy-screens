# SuperHeavy Screens - MVP Workout Training App

Um MVP de aplicação de treino inspirado no app **Hevy**, desenvolvido apenas com **HTML e CSS** (sem JavaScript).

## 📱 Funcionalidades

### 1. Tela de Configuração de Workout
- **Cadastro de Treino**: Nome do workout e grupo muscular
- **Gerenciamento de Exercícios**: 
  - Nome do exercício
  - Peso (kg)
  - Repetições
  - Séries
  - Tempo de descanso

### 2. Tela de Execução de Treino
Baseada no design do app Hevy com:
- Lista de exercícios com séries organizadas
- Indicadores visuais de peso/repetições
- Controle de séries (W = Warmup, números = séries normais, F = Failure)
- Timer de descanso entre séries
- Botão "Add Set" para adicionar novas séries
- Progresso visual das séries completadas (checkmarks verdes)

## 🎨 Design Inspirado no Hevy

O layout replica as principais características visuais do Hevy:
- **Interface clean e minimalista**
- **Cards de exercícios** com informações organizadas
- **Sistema de cores**: 
  - Verde para séries completadas ✅
  - Azul para elementos interativos
  - Cinza para informações secundárias
- **Typography moderna** e legível
- **Layout responsivo** para mobile

## 📁 Estrutura do Projeto

```
superheavy-screens/
├── index.html              # Página principal
├── css/
│   ├── style.css           # Estilos principais
│   ├── workout-config.css  # Estilos da tela de configuração
│   └── workout-execution.css # Estilos da tela de execução
├── pages/
│   ├── workout-config.html # Tela de configuração
│   └── workout-execution.html # Tela de execução
└── README.md
```

## 🚀 Como Usar

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/SEU_USUARIO/superheavy-screens.git
   cd superheavy-screens
   ```

2. **Abra no navegador:**
   ```bash
   open index.html
   # ou
   python -m http.server 8000  # Para servir localmente
   ```

3. **Navegação:**
   - `index.html` - Página inicial com navegação
   - `pages/workout-config.html` - Configuração de treinos
   - `pages/workout-execution.html` - Execução de treinos

## 🎯 Funcionalidades Implementadas (HTML/CSS apenas)

### Tela de Configuração
- [x] Formulário de cadastro de workout
- [x] Campos para nome e grupo muscular
- [x] Seção de exercícios com peso, reps, séries e tempo
- [x] Layout responsivo mobile-first
- [x] Validação visual com CSS

### Tela de Execução
- [x] Réplica visual do app Hevy
- [x] Cards de exercícios organizados
- [x] Sistema visual de séries (W, 1, 2, 3, F)
- [x] Indicadores de peso e repetições
- [x] Botões "Add Set" estilizados
- [x] Timer visual de descanso
- [x] Checkmarks para séries completadas
- [x] Animações CSS para feedback visual

## 🎨 Elementos Visuais Principais

### Cards de Exercícios
- **Header** com nome do exercício e ícone
- **Descrição** do exercício (quando disponível)
- **Grid de séries** com peso e repetições
- **Timer de descanso** com design circular
- **Botão "Add Set"** com estilo Hevy

### Sistema de Cores
```css
:root {
  --primary-blue: #007AFF;
  --success-green: #34C759;
  --background-gray: #F2F2F7;
  --text-primary: #000000;
  --text-secondary: #8E8E93;
  --card-background: #FFFFFF;
}
```

## 📱 Responsividade

- **Mobile First**: Otimizado para dispositivos móveis
- **Breakpoints**: Adaptável para tablets e desktop
- **Touch Friendly**: Elementos com tamanho adequado para toque

## 🔧 Limitações (Somente HTML/CSS)

- Dados são estáticos (não há persistência)
- Interações limitadas a :hover, :focus, :checked
- Timer funcional apenas visual
- Navegação via links HTML

## 🎯 Próximos Passos (Futuras Implementações)

1. **JavaScript** para funcionalidade dinâmica
2. **LocalStorage** para persistência de dados
3. **Timer funcional** para descanso
4. **PWA** para instalação mobile
5. **Backend** para sincronização de dados

## 📝 Inspiração

Este projeto é inspirado no excelente app **Hevy** - um dos melhores aplicativos de treino disponíveis. O objetivo é recriar sua interface limpa e funcional usando apenas tecnologias web básicas.

## 📄 Licença

MIT License - Sinta-se livre para usar e modificar este projeto.
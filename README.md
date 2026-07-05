# Web3 Workshops

Workshops práticos de Web3 de que participei — este repo é o índice: tema, ideia central e stack de cada um. O material trabalhado (anotações, exercícios e código) será publicado aqui aos poucos, workshop a workshop.

## Workshops

### ⚓ Solana na Prática: Fundamentos, Ferramentas e Primeiro Deploy
*2026-06-28 · instrutor Kaue (Web3 Experts Brazil) · Solana · Anchor (Rust) · devnet*

Do zero ao primeiro programa rodando na Solana: modelo de contas, PDAs (Program Derived Addresses), o framework Anchor e o ciclo completo build → test → deploy na devnet. O exercício central é um programa de contador por usuário — cada `authority` tem sua própria conta derivada por PDA, com proteção de overflow e validação de dono.

### 🛡️ Guardrails em Solidity: Projetando Contratos para Erros Desconhecidos
*2026-06-27 · Web3 Experts Brazil · Solidity · Foundry · OpenZeppelin*

Como projetar contratos que sobrevivem a erros que você ainda não conhece: guardrails de inicialização (a classe de bug do hack da Parity), padrões de proxy/upgrade seguros e proteções em vaults ERC-4626. Formato mão na massa: contratos deliberadamente vulneráveis, exploit e correção lado a lado.

### 🪄 Melhorando a UX Onchain com Account Abstraction
*2026-06-27 · palestrante Jony Reis, CTO Chainless (Chainless by Notus) · ERC-4337 · Web3Auth/MPC*

A maior barreira de adoção onchain é a UX: seed phrase, gas em token nativo, pop-up de carteira a cada clique. Account Abstraction ataca cada um desses pontos com smart accounts programáveis — login social sem seed phrase, gasless via Paymaster, batching de ações e session keys — com comparação entre ERC-4337 e ERC-7702.

### 👛 Construção de uma Carteira Web3 com Embedded Wallets
*2026-06-27 · Web3 Experts Brazil · React + Vite · Privy · Pods*

Construção de uma carteira Web3 completa, com cara de produto: autenticação via Privy com criação de embedded wallet, smart wallet como único endereço exibido e executável, leitura de saldos e histórico, fluxos de depósito e envio de cripto, swap e earn via widgets, e execução de transações pela smart wallet. O exercício mostra como embedded + smart wallets eliminam a seed phrase da experiência do usuário.

---

*Repo em construção — o material de cada workshop entra aqui conforme for revisado para publicação.*

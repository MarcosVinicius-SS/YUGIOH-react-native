# 🎴 Yu-Gi-Oh CRUD — React Native + Expo + Node.js

## 📁 Estrutura
```
yugioh-crud/
├── backend/
│   ├── server.js      ← API Express
│   ├── db.json        ← Banco de dados (JSON)
│   └── package.json
└── frontend/
    ├── App.js         ← Navegação principal
    ├── api.js         ← Conexão com o backend
    ├── telas/
    │   ├── TelaCartas.js     ← Puxar cartas + favoritar
    │   └── TelaFavoritos.js  ← CRUD de favoritos
    └── package.json
```

## 🚀 Como rodar

### 1. Backend (rode primeiro!)
```bash
cd backend
npm install
npm run dev
```
API rodando em: http://localhost:3001

### 2. Frontend
```bash
cd frontend
npm install
npx expo start
```

### 3. Rotas da API
| Método | Rota              | Descrição         |
|--------|-------------------|-------------------|
| GET    | /favoritos        | Listar favoritos  |
| POST   | /favoritos        | Adicionar favorito|
| PUT    | /favoritos/:id    | Editar nota       |
| DELETE | /favoritos/:id    | Remover favorito  |

## 📱 Funcionalidades
- Puxar carta aleatória da API YGOPRODeck
- Adicionar carta ao baralho de favoritos
- Ver lista de cartas favoritadas
- Editar nota pessoal de cada carta
- Remover carta dos favoritos

## ⚠️ Celular físico
Edite o arquivo `api.js` e coloque o IP da sua máquina:
```javascript
return 'http://192.168.X.X:3001'; // seu IP local
```

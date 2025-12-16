# Global Financial Account Process API

API Process qui agit comme proxy/pass-through vers Global Financial Account System API.

## Description

Cette API fournit un point d'entrée Process API pour accéder aux comptes financiers, transactions et cartes dans Global Data. Elle fait un pass-through vers Global Financial Account System API.

## Endpoints

Identiques à Global Financial Account System API:
- GET /api/process/global/accounts
- POST /api/process/global/accounts
- GET /api/process/global/accounts/{accountGlobalId}
- GET /api/process/global/accounts/transactions
- POST /api/process/global/accounts/transactions
- GET /api/process/global/accounts/cards
- POST /api/process/global/accounts/cards

## Configuration

### Connexions HTTP Requises

- **Global Financial Account System API** (port 8081)

Configurer dans `global.xml`:
- `Global_Financial_Account_System_API_Config`

### Port

- **Port HTTP**: 8082


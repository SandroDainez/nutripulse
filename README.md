# NutriPulse

Diário de nutrição e hidratação: calorias, macros, água e histórico por data. Os dados ficam no navegador (`localStorage`) e o app pode ser instalado (PWA).

## Como usar

Abra o site na Vercel ou rode localmente. No primeiro uso, preencha o **Perfil** para calcular a meta calórica (Mifflin-St Jeor), proteínas (~1,8 g/kg), água (~35 ml/kg) e o IMC.

Valores da tabela rápida são por **100 g** (TACO/TBCA). Dá para criar alimentos próprios, editar porções, copiar o dia anterior, exportar/importar backup e usar offline depois da primeira visita.

## Desenvolvimento

Não há build. É um site estático:

```bash
npx serve .
```

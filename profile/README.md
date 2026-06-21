<div align="center">

<img src="https://raw.githubusercontent.com/cucuapi/.github/main/profile/assets/cucu.png" width="120" alt="CUCU" />

# CUCU

**Software que mueve empresas. Infraestructura que mueve activos cripto.**

<br>

🤖 &nbsp;**AI agents** · MCP &nbsp;&nbsp;·&nbsp;&nbsp; ☸️ &nbsp;**Kubernetes**-native &nbsp;&nbsp;·&nbsp;&nbsp; 🟣 &nbsp;**Odoo** modules &nbsp;&nbsp;·&nbsp;&nbsp; ⚡ &nbsp;**QR** interoperable &nbsp;&nbsp;·&nbsp;&nbsp; ₮ &nbsp;**USDT · USDC** payments

<sub>La Paz, Bolivia 🇧🇴 &nbsp;·&nbsp; [cucu.bo](https://www.cucu.bo) &nbsp;·&nbsp; [cucu.ai](https://www.cucu.ai)</sub>

</div>

---

<br>

### cucu.bo &nbsp;—&nbsp; Automatización empresarial

<div align="center">

<img src="https://raw.githubusercontent.com/cucuapi/.github/main/profile/assets/cucubo.svg" width="540" alt="cucu.bo stack" />

</div>

<br>

```bash
curl -X POST https://api.cucu.bo/v1/invoices \
  -H "Authorization: Bearer $CUCU_API_KEY" \
  -d '{ "nit": "123456789", "cliente": "EMPRESA S.R.L.", "total": 1500.00 }'
```

```json
{ "cuf": "E2B5A9F3C1...", "estado": "VALIDADA", "cufd": "A0B1C2..." }
```

&nbsp;&nbsp;→ **[cucu.bo](https://www.cucu.bo)**

<br>

---

<br>

### CUCU FINTECH &nbsp;—&nbsp; Infraestructura de pagos cripto-nativa

<div align="center">

<img src="https://raw.githubusercontent.com/cucuapi/.github/main/profile/assets/architecture.svg" width="520" alt="CUCU CORE architecture" />

</div>

<br>

```bash
curl -X POST https://api.cucu.ai/v1/accounts \
  -H "Authorization: Bearer $CUCU_API_KEY" \
  -d '{ "user_id": "u_42", "tokens": ["USDT", "USDC", "BTC"] }'
```

```json
{
  "id": "acc_01HXY...",
  "wallets": [
    { "token": "USDT", "address": "0x9a3...", "network": "tron"     },
    { "token": "USDC", "address": "0x4b1...", "network": "ethereum" },
    { "token": "BTC",  "address": "bc1q...",  "network": "bitcoin"  }
  ]
}
```

<br>

<div align="center">

<img src="https://cdn.jsdelivr.net/gh/spothq/cryptocurrency-icons@master/svg/color/usdt.svg" width="52" alt="USDT" />&nbsp;&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/spothq/cryptocurrency-icons@master/svg/color/usdc.svg" width="52" alt="USDC" />&nbsp;&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/spothq/cryptocurrency-icons@master/svg/color/trx.svg"  width="52" alt="TRX"  />&nbsp;&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/spothq/cryptocurrency-icons@master/svg/color/bnb.svg"  width="52" alt="BNB"  />&nbsp;&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/spothq/cryptocurrency-icons@master/svg/color/eth.svg"  width="52" alt="ETH"  />&nbsp;&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/spothq/cryptocurrency-icons@master/svg/color/btc.svg"  width="52" alt="BTC"  />

</div>

<br>

&nbsp;&nbsp;→ **[cucu.ai](https://www.cucu.ai)**

<br>

---

<div align="center">
<sub>api@cucu.bo</sub>
</div>

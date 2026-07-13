# Bunker Marcas e Patentes — Landing Page

Landing page de conversão para captação de leads, desenvolvida para a Bunker
Marcas e Patentes, oferecendo uma **Busca de Viabilidade gratuita** para
registro de marcas.

## Funcionalidades

- Formulário de lead com validação client-side (nome, e-mail, CNPJ com
  dígitos verificadores, WhatsApp)
- Máscaras automáticas de CNPJ e telefone durante a digitação
- Proteção anti-bot: honeypot field + reCAPTCHA v3 + timing check
- Captura e persistência de parâmetros UTM (sessionStorage)
- Integração com Google Apps Script para envio de leads (Sheets + e-mail)
- Botão flutuante de WhatsApp e botão de voltar ao topo
- Design responsivo, sem dependências de build (HTML/CSS/JS puro)

## Stack

HTML5, CSS3, JavaScript vanilla. Fontes via Google Fonts (Manrope, Space Mono).

## Como usar

Abra o arquivo `index.html` diretamente no navegador ou hospede em qualquer
servidor estático. Antes de publicar, configure:

- `APPS_SCRIPT_URL`: URL de implantação do Google Apps Script
- `RECAPTCHA_SITE_KEY`: chave do reCAPTCHA v3
- Tags de tracking (GTM/GA4/Meta Pixel), conforme comentário no `<head>`

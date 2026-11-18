# DropSystem OS 🟣

Sistema operacional baseado em Debian, Xfce e Wine, feito para ser leve, completo e fácil de usar.

## ✅ Funcionalidades

- Interface Xfce personalizada
- Wine pré-instalado para aplicativos `.exe` do Windows
- Navegador, pacote de escritório e reprodutor de mídia
- Instalador gráfico Calamares
- Tela de inicialização personalizada

## 📥 Download

Acesse a página de [Releases](https://github.com/EmbrasilSeguranca/dropsystem-os/releases) e baixe a imagem `.iso`.

## 🔧 Compilar localmente

```bash
sudo apt-get install live-build
lb clean
./auto/config
./auto/build
```

## 🚀 Publicar uma versão

```bash
git tag -a v1.0 -m "Versão 1.0 do DropSystem OS"
git push origin v1.0
```

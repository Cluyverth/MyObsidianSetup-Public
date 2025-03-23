# **Obsidian Vault Setup** 📝🚀

Este repositório contém a configuração e personalização do meu **Obsidian Vault**, incluindo temas, plugins e estrutura de organização.

## **📌 Requisitos**

Antes de configurar o Vault, certifique-se de ter:

- [**Obsidian**](https://obsidian.md/) instalado no seu sistema.
    
- **Git** (opcional, para versionamento e sincronização).
    

## **📂 Estrutura do Vault**

A estrutura principal do Vault segue este modelo:

```
/ObsidianVault
│── 📁 Atlas
	│── 📁 MOCs
	│── 📁 Notes
	│── 📁 Utilities
		│── 📁 Images
		│── 📁 Library
│── 📁 Calendar
	│── 📁 Notes
│── 📁 Dashboard
│── 📁 Settings
	│── 📁 Backgrounds
	│── 📁 Templates
│── obsidian.json
│── .gitignore
```

📌 **Explicação:**

- **Atlas** → MOCs, Todas as Notas, Imagens, documentos e PDFs.
    
- **Calendar** → Daily Notes organizadas por dia.
    
- **Dashboard** → Dashboards.
    
- **Settings** → Backgrounds e Templates.

---

## **⚙️ Configuração**

1. **Clone este repositório:**
    

```
git clone https://github.com/Cluyverth/MyObsidianSetup-Public.git
```

2. **Abra no Obsidian:**
    
    - No **Obsidian**, clique em **Open folder as Vault** e selecione a pasta clonada.
        
3. **Ative Plugins e Temas:**
    
    - Vá até **Settings → Community Plugins** e ative os plugins necessários.
        
    - Selecione o tema desejado em **Settings → Appearance**.
        

---

## **🔌 Plugins Utilizados**

Aqui estão alguns dos plugins usados no Vault:

- ✅ **Dataview**
- ✅ **Advanced Tables**
- ✅ **Tasks**
- ✅ **Excalidraw**
- ✅ **Style Settings**
- ✅ **Calendar**
- ✅ **Callout Manager**
- ✅ **Commander**
- ✅ **Recent Files**
- ✅ **Spaced Repetition**
- ✅ **Workspace Plus**
- ✅ **Git**
- ✅ **Iconize**

Para instalar plugins:

1. Acesse **Settings → Community Plugins**
    
2. Clique em **Browse** e pesquise pelo nome do plugin
    
3. Instale e ative os desejados
    

---

## **☁️ Sincronização com Git** (Opcional)

Caso queira sincronizar suas notas via GitHub:

1. **Configurar Git no Vault:**
    

```
git init
git remote add origin https://github.com/seu-usuario/seu-repo.git
```

2. **Adicionar e commitar mudanças:**
    

```
git add .
git commit -m "Atualizando Vault"
git push origin main
```

Para manter o Vault sempre atualizado, basta rodar:

```
git pull origin main
```

---

## **📜 Licença**

Este repositório segue a licença **MIT**. Fique à vontade para usar e modificar conforme necessário.
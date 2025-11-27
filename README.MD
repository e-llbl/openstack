# OpenStack - Instalação All-in-One

Este repositório contém scripts para configurar um ambiente **OpenStack** em modo *all-in-one host*.

## 🚀 Passo a passo de instalação

### 1. Clone o repositório
```bash
git clone https://github.com/e-llbl/openstack
```

### 2. Acesse a pasta do projeto
```bash
cd openstack
```

### 3. Configure as variáveis
Edite o arquivo `variaveis.sh` e preencha todas as variáveis necessárias:
```bash
sudo nano variaveis.sh
```

### 4. Torne os scripts executáveis
```bash
sudo chmod +x *.sh
```

### 5. Execute o script principal
```bash
sudo ./b1_all-in-one_host.sh
```

---

## 📌 Observações
- Certifique-se de ter privilégios de administrador (sudo).
- Revise o arquivo `variaveis.sh` com atenção antes de executar os scripts.
- Este projeto é destinado a ambientes de teste e aprendizado.

---
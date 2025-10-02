# 🦜 Papagaio

## Objetivo
O projeto **Papagaio** tem como objetivo construir modelos de aprendizado profundo para classificar espécies de aves a partir de imagens. Ele utiliza técnicas de redes neurais convolucionais e aprendizado por transferência, com foco em espécies de psitacídeos do cerrado brasileiro.

## Sobre as aves
As aves do dataset pertencem à família **Psittacidae**, um dos grupos mais inteligentes do reino animal, conhecidos por sua capacidade de imitar sons e pela longevidade, algumas espécies vivendo mais de 50 anos. São aves com características únicas, como forte desenvolvimento cerebral, socialização intensa e grande diversidade de cores e tamanhos. 

O dataset está disponível em: [Google Drive](https://drive.google.com/file/d/19rWCGW38ht8TLY1ad7gba46mP5FCIZul/view)

## Espécies do dataset
O conjunto de dados inclui 14 espécies de psitacídeos:  

- **Amazona aestiva** – Papagaio-verdadeiro  
- **Amazona amazonica** – Curica  
- **Anodorhynchus hyacinthinus** – Arara-azul  
- **Ara ararauna** – Arara-canindé  
- **Ara chloropterus** – Arara-vermelha  
- **Ara macao** – Araracanga  
- **Brotogeris chiriri** – Periquito-de-encontro-amarelo  
- **Diopsittaca nobilis** – Maracanã-pequena  
- **Eupsittula aurea** – Periquito-rei  
- **Forpus xanthopterygius** – Tuim  
- **Orthopsittaca manilatus** – Maracanã-do-buriti  
- **Primolius maracana** – Maracanã  
- **Psittacara leucophthalmus** – Periquitão  
- **Touit melanonotus** – Apuim-de-costas-pretas  

O dataset foi adaptado a partir do [iNaturalist](https://www.inaturalist.org), uma plataforma colaborativa de ciência cidadã onde usuários do mundo todo registram e compartilham observações de espécies da fauna e flora.  

Mais informações sobre a família podem ser encontradas no [WikiAves](https://www.wikiaves.com.br/wiki/psittacidae).   

---

## Como rodar o projeto (Local)

### 1. Criar e ativar a virtualenv
```bash
python -m venv venv
# Linux/Mac
source venv/bin/activate

# Windows
venv\Scripts\activate
```

### 2. Instalar as dependências
```bash
pip install -r requirements.txt
```

### 3. Iniciar o Jupyter Lab
```bash
jupyter lab
```
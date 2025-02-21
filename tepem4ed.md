# TEPEM for Education - TEPEM4Ed

TEPEM4Ed (TEPEM for Education) é um software de simulação do escoamento sanguíneo 3d, desenvolvido para a primeira edição do minicurso "Introdução à Hemodinâmica Computacional" (2023) que encapsula dentro de um container Docker o método numérico denominado TEPEM (Transversally Enriched Pipe Element Method). 
O TEPEM foi desenvolvido durante a tese de doutorado do Alonso Alvarez, sob orientação do Pablo Blanco, no LNCC.

- Pablo Blanco. Pesquisador Títular do LNCC. pjblanco [at] lncc.br
- Alonso Alvarez. Pesquisador Adjunto do LNCc. lalvarez [at] lncc.br

Links de interesse:
- Laboratório Nacional de Computação Científica: [LNCC](https://lncc.br)
- Programa de Verão do LNCC: [PV-LNCC](https://verao.lncc.br)
- Hemodynamics Modeling Laboratory: [HeMoLab](http://hemolab.lncc.br)

Para clonar este repositório:
   ```bash
   git clone https://github.com/alonso-alvarez/PVLNCC_IntroHemodinamicaComputacional
  ```

## Requisitos
- **Docker** Recomendamos o seguinte tutorial: [Instalar Docker](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-20-04)
- **Visualização.** Para a visualização dos resultados, utilizaremos o conhecido software [Paraview](https://www.paraview.org/download/)

## TEPEM4Ed como docker container
<img src="imageFolder/docker_process.png" width="700"/>

Comandos uteis no Docker:
- **Listar imagens.** docker image list
- **Buscar imagens.** docker search hemolab
- **Utilizar imagen.** docker run -it hemolab/tepem4ed

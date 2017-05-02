# TCCproject
Projeto TCC Artefato em anel - Tomografia
Objetivo: retirar ou minimizar artefatos em anel provenientes de imagens de tomografia.
Ferramenta utilizada: ImageJ plugins.
A primeira parte do projeto será a implementação da classe que detecta as colunas com artefatos (artefatos em anel).
Primeiro passo:
Transformação da imagem em coordenadas polares (transformação de circulos em retas).
class Polar-Transfomer disponível no internet

Segundo passo:
criação da classe que detecta as colunas com artefatos: 
divisão em duas classes: Estatisticas_Coluna e Detector_de_Colunas
Estatisticas_Colunas vai ter métodos que retornam as estatísticas importantes de uma coluna especificada (média, desvio padrão, histograma...)
OBS:Estatisticas_Colunas é o objetivo de estudo no momento. Ver classes a seguir

# Fundamentos em Informática Médica e Telemedicina

## Projeto AB2

### Análise de imagens médicas e definição de atributos de identificação com o software ImageJ/Fiji com Trainable Weka Segmentation.

## Grupo:
* Eric Araújo;
* Luís Gustavo Rocha;
* Maxwell Acioli.

## Professor:
* Marcelo Costa Oliveira

## Objetivo:

* Extração de Atributos de Nódulos Pulmonares
  * Imagem de Tomografia Computadorizada
    * Nódulo de Câncer de Pulmão
    * Nódulo foi Segmentado Manualmente
    * Disponível em:
      * [Dropbox Content](https://dl.dropboxusercontent.com/u/11507361/noduloSegmentado.tar)

## Ferramentas Utilizadas:

* Software: [Fiji](https://fiji.sc/) com o plugin Trainable Weka Segmentation.

## Procedimento

1. Ao abrimos a ferramenta Fiji, abrimos o plugin Trainable Weka Segmentation;

2. Carregamos a imagem (nodulo35) no plugin;

  ![alt tag](https://github.com/LedZeck/telemedicina2016-1/blob/master/Images/Image-nodulo.PNG)

3. Em seguida foram selecionadas as regiões na imagem para cada classe, então foi gerada a classificação com as regioes demarcadas;

  ![alt tag](https://github.com/LedZeck/telemedicina2016-1/blob/master/Images/Image-1.PNG)

4. Foi salvo o resultado em ("Save data") um formato .arff;

5. Abrimos o Weka Explorer e abrimos o resultado salvo, desta forma foi possível observar que obtivemos 80 atributos, dentro os quais escolhemos dez para apresentar os gráficos dos mesmos;

  ![alt tag](https://github.com/LedZeck/telemedicina2016-1/blob/master/Images/Image-0.PNG)

6. Os atributos escolhidos foram os das imagens abaixo:

  6.1 Hessian_Trace_16.0(Num)

  ![alt tag](https://github.com/LedZeck/telemedicina2016-1/blob/master/Images/Image-2.PNG)

  6.2 Hessian_Determinant_16.0(Num)

  ![alt tag](https://github.com/LedZeck/telemedicina2016-1/blob/master/Images/Image-3.PNG)

  6.3 Sobel_Filter_8.0(Num)

  ![alt tag](https://github.com/LedZeck/telemedicina2016-1/blob/master/Images/Image-4.PNG)

  6.4 Brightness(Num)

  ![alt tag](https://github.com/LedZeck/telemedicina2016-1/blob/master/Images/Image-5.PNG)

  6.5 Hessian_Determinant_0.0(Num)

  ![alt tag](https://github.com/LedZeck/telemedicina2016-1/blob/master/Images/Image-6.PNG)

  6.6 Hessian_Normalized_Eigenvalue_Difference_2.0(Num)

  ![alt tag](https://github.com/LedZeck/telemedicina2016-1/blob/master/Images/Image-7.PNG)

  6.7 Difference_of_gaussians_8.0_2.0(Num)

  ![alt tag](https://github.com/LedZeck/telemedicina2016-1/blob/master/Images/Image-8.PNG)

  6.8 Membrane_Projections_5_19_1(Num)

  ![alt tag](https://github.com/LedZeck/telemedicina2016-1/blob/master/Images/Image-9.PNG)

  6.9 Hessian_2.0(Num)

  ![alt tag](https://github.com/LedZeck/telemedicina2016-1/blob/master/Images/Image-10.PNG)

  6.10 Hessian_Orientation_0.0(Num)

  ![alt tag](https://github.com/LedZeck/telemedicina2016-1/blob/master/Images/Image-11.PNG)

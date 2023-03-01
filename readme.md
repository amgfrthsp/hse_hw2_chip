Для анализа была выбрана клеточная линия HeLa-S3 и гистоновая метка H3K4me3.

# FastQC
html-отчеты для разных файлов:

[1-я реплика](https://github.com/amgfrthsp/hse_hw2_chip/blob/main/data/ENCFF001FLG_fastqc.html)

![image](https://raw.githubusercontent.com/amgfrthsp/hse_hw2_chip/main/data/1.png)

Видно, что есть проблемы с файлом. Проделала дополнительные подрезания и фильтрацию. 

[2-я реплика](https://github.com/amgfrthsp/hse_hw2_chip/blob/main/data/ENCFF000BDA_fastqc.html)

![image](https://raw.githubusercontent.com/amgfrthsp/hse_hw2_chip/main/data/2.png)

Здесь все ок

[контроль](https://github.com/amgfrthsp/hse_hw2_chip/blob/main/data/ENCFF001HNS_fastqc.html)

![image](https://raw.githubusercontent.com/amgfrthsp/hse_hw2_chip/main/data/3.png)

Здесь все ок

# Выравнивание на 16 хромосому

Таблица

![image](https://raw.githubusercontent.com/amgfrthsp/hse_hw2_chip/main/data/table.png)

# Диаграммы Эйлера-Венна
## Пересечение пиков 1 реплики и ENCODE
### 1-я реплика с ENCODE

![image](https://raw.githubusercontent.com/amgfrthsp/hse_hw2_chip/main/data/Intervene_venn-1.png)

### ENCODE с 1-й репликой

![image](https://raw.githubusercontent.com/amgfrthsp/hse_hw2_chip/main/data/Intervene_venn%20(1)-1.png)

### 2-я реплика с ENCODE

![image](https://raw.githubusercontent.com/amgfrthsp/hse_hw2_chip/main/data/Intervene_venn%20(2)-1.png)

### ENCODE с 2-й репликой

![image](https://raw.githubusercontent.com/amgfrthsp/hse_hw2_chip/main/data/Intervene_venn%20(3)-1.png)


Так как мы выравнивали только на одну хромосому, пересечений получилось мало. 
В базе ENCODE пиков значительно больше, поскольку они составлены для всех хромосом.


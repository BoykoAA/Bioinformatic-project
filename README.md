Проект созданный на летней школе биоинформатики.
LUAD vs LUSC project.

В TCGA базе данных есть данные по большому количеству разных типов рака. В рамках проекта мы хотим посмотреть на два вида рака легких (lung adenocarcinoma and lung squamous cell carcinoma) и на мутации, которые в них происходят.

Как мы узнали на практике, эти виды рака достаточно просто различаются по данным метилирования, однако меня интересует чуть более сложная и чуть более шумная задача.

В рамках проекта, мы должны найти гены, мутационные сигнатуры которых определяют один вид рака, но не другой.

Ссылки на статьи про LUAD (https://www.nature.com/articles/nature13385.pdf) и про LUSC (https://www.nature.com/articles/nature11404.pdf).

Мы будем работать с двумя файлами MAF-формата, описание которого можно найти https://docs.gdc.cancer.gov/Data/File_Formats/MAF_Format/



Datasets: https://portal.gdc.cancer.gov/repository
Repository
Choose Cases / TCGA / LUNG / TCGA-LUAD / TCGA-LUSC
Choose Files / Open Access / MAF file format /Mutect2 aggregation tool
Find MAF files


case_id column is donor ID
Hugo_symbol is gene name



# hse_hw4_hic  
### Ссылка на colab:  
https://colab.research.google.com/drive/14lPhyqTpsxZBgMRpoZTyz9fQfz2nC2vq?usp=sharing  
### Выбор участка и хромосомы:  
хромосома 3R и участок 8,500,000-10,000,000  
### Выполнение пунктов задания и ответы на вопросы: 
*Последовательно вставленные скриншоты четырех реплик соответствуют их последовательности  

#### a. получить информацию и атрибуты матрицы Hi-C с помощью cooler.info 
![image](https://github.com/GO-KPRO/hse_hw4_hic/assets/98886243/7147ba23-d97b-41fc-83f1-ace83389f84e)  
![image](https://github.com/GO-KPRO/hse_hw4_hic/assets/98886243/ee4fca0d-5893-45ab-b9ee-f3d6d3e5ad7d)  
![image](https://github.com/GO-KPRO/hse_hw4_hic/assets/98886243/5bbec458-a27b-4bc6-8b6b-938e4164f301)  
![image](https://github.com/GO-KPRO/hse_hw4_hic/assets/98886243/429a32f1-f374-44ad-915e-521220b47554)  

#### b. открыть объект cooler как сбалансированную матрицу для внутрихромосомных контактов  
![image](https://github.com/GO-KPRO/hse_hw4_hic/assets/98886243/8dad6e4a-9005-48f9-bd20-dda23900b6fd)  
![image](https://github.com/GO-KPRO/hse_hw4_hic/assets/98886243/d12833e9-809d-4ef7-9e34-3119b5d8c9f4)  
![image](https://github.com/GO-KPRO/hse_hw4_hic/assets/98886243/9fb32b99-e8b1-4198-8465-3fb3bc689e78)  
![image](https://github.com/GO-KPRO/hse_hw4_hic/assets/98886243/c745ae64-9088-44a3-9bb2-b4ac6b47074b)  
Также решено было отрисовать хитмапы нашего участка для наглядности:  
![image](https://github.com/GO-KPRO/hse_hw4_hic/assets/98886243/8282d287-3a91-43e1-b865-6948298ca3e4)  
![image](https://github.com/GO-KPRO/hse_hw4_hic/assets/98886243/b3b15f36-0453-490b-bc68-c6e39f804181)  
![image](https://github.com/GO-KPRO/hse_hw4_hic/assets/98886243/6ddc301a-d871-47f6-ac0e-53783d4f4d3d)  
![image](https://github.com/GO-KPRO/hse_hw4_hic/assets/98886243/f87b910b-2d20-45f7-bd69-9384aca7816b)  

#### c. получить таблицу с координатами и контактами, они сбалансированные или нет?  
![image](https://github.com/GO-KPRO/hse_hw4_hic/assets/98886243/2730c70d-da30-4274-990e-fa3a6d9cb1d4)  
![image](https://github.com/GO-KPRO/hse_hw4_hic/assets/98886243/a11730ff-3a80-4ee4-a6a4-ad129366cdba)  
![image](https://github.com/GO-KPRO/hse_hw4_hic/assets/98886243/c8600c05-ead5-4d29-8bcb-db566e24555e)  
![image](https://github.com/GO-KPRO/hse_hw4_hic/assets/98886243/97294a16-fcc1-48a6-a7c1-1d7088ba4140)  

Ответ: В колонке count данные дополнительно не обработаны, поэтому их вполне можно назвать несбалансированными.  

#### d. получить таблицу в командной строке командой *cooler dump*  
![image](https://github.com/GO-KPRO/hse_hw4_hic/assets/98886243/c1766825-4260-4757-ac4b-bc94e5be83e4)  
Полученные таблицы лежат в папке tables  

#### e. посмотрите таблицу с бинами, какие столбцы там присутствуют?  

#### f. постройте кривые зависимости число контактов от расстояния для выбранной хромосомы (в логарифмических-координатах) для 4х реплик. Сравните их.  

#### g. для выбранного участка найдите insulation score и границы тадов для всех реплик   

#### h. сравните результаты и постройте графики полученных кривых. Отобразите на них границы  ТАДов.  

#### i. Создайте 4 bed файла с границами ТАДов.В поле score добавьте силу границы.  


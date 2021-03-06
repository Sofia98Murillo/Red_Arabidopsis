# Red_Arabidopsis
![Arabidopsis-thaliana-(L )-Heynh -434632](https://user-images.githubusercontent.com/67028105/85800833-4811c680-b707-11ea-871c-1cf93de404f8.jpg)

- La tolerancia a la desecación (DT) es un proceso notable que permite a las semilas sobrevivir largos períodos de agua escasa hasta que se presenten condiciones favorables para la germinación

- Se ha postulado que la DT de las semillas evolucionó al reconectar las redes reguladoras y de señalización que controlaban el DT vegetativa

- Entender las redes que regulan la tolerancia a la desecación de semillas en los sistemas de plantas modelo proporcionaría las herramientas para entender un proceso evolutivo que jugó un papel crucial en la diversificación de las plantas en floración.

                         -En Arabidopsis, el desarrollo embrionario y la maduración de semillas, incluyendo la adquisición de DT, 
                         es orquestada por un conjunto de cuatro reguladores principales: 
                         - LEAFY COTYLEDON 1 (LEC1)
                         - CCAAT factor de unión A caja
                         - Tres proteínas que contienen B3 (12), ABSCISIC ACID INSENSITIVE 3 (ABI3), FUSCA 3 (FUS3), y LEC2.

# RED
De la red Tfsseed-subNetDT1( descrita en el artículo siguiente https://www.pnas.org/content/pnas/113/35/E5232.full.pdf )implicada en el almacenamiento de nutrientes y tolerancia al estrés, se escogieron los genes: 
- GASA3: proteína_Gibberellin-regulated protein 3. Es una giberelina , proteína reguladura que puede funcionar en etapas de desarrollo hormonales controladas como germinación de semillas, floración y maduración de semillas.
- HVA22B:proteína_HVA22-like protein b. 

         - En el artículo se encuentran en un la categoría funcional de metabolismo hormonal.

Formato FASTA de las proteínas:
>sp|Q9SYX7|HA22B_ARATH HVA22-like protein b OS=Arabidopsis thaliana OX=3702 GN=HVA22B PE=2 SV=2
MSSGIGSLVKVIFKNFDVIAGPVISLVYPLYASVRAIESRSHGDDKQWLTYWALYSLIKL
FELTFFRLLEWIPLYPYAKLALTSWLVLPGMNGAAYLYEHYVRSFLLSPHTVNVWYVPAK
KDDDLGATAGKFTPVNDSGAPQEKIVSSVDTSAKYVGHSAFDDAYIY
>sp|P46687|GASA3_ARATH Gibberellin-regulated protein 3 OS=Arabidopsis thaliana OX=3702 GN=GASA3 PE=2 SV=1
MAIFRSTLVLLLILFCLTTFELHVHAAEDSQVGEGVVKIDCGGRCKGRCSKSSRPNLCLR
ACNSCCYRCNCVPPGTAGNHHLCPCYASITTRGGRLKCP

Se creo ésta red usando genemania.org

![Imagen2](https://user-images.githubusercontent.com/67028105/85803998-18b28800-b70e-11ea-8b9b-7f4640a848f5.jpg)

                                         -Las línas verdes representan dominios proteicos compartidos y las moradas co-expresión

![Imagen1](https://user-images.githubusercontent.com/67028105/85803913-e43ecc00-b70d-11ea-9b43-0237b487612f.jpg)


>En la red se pueden observar que estos genes interaccionan con otros genes que codifican para giberelinas y por genes que expresan para prteínas que se pueden inducir por ABA y por estrés.

>Co-expresión: Datos de expresión génica. Dos genes están vinculados si sus niveles de expresión son similares a través de condiciones en un estudio de expresión génica. La mayoría de estos datos se recogen del Gene Expression Omnibus (GEO)

>Dominios de proteínas compartidos: Datos de dominio de proteínas. Dos productos génicos están vinculados si tienen el mismo dominio de proteínas. Estos datos se recogen de bases de datos de dominio, como Interpro, SMART y Pfam.

Entre estos dos genes Genemania no muestra vinculaciones en interacciones físicas, co-localización, interacciones genéticas y predicción funcional.

![Imagen3](https://user-images.githubusercontent.com/67028105/85805865-14d53480-b713-11ea-9220-7eb804059b76.png)

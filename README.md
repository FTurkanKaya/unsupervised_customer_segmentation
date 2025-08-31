# Ongecontroleerde-Klantsegmentatie

Deze repository bevat een volledige workflow voor klantsegmentatie met behulp van KMeans en Hiërarchische Clustering, twee populaire unsupervised learning-methoden. Het doel is om klanten te groeperen op basis van transactiegegevens, waaronder online en offline aankopen, Recency, Frequency en Monetary (RFM) metrics. Dit helpt bedrijven bij gerichte marketing, klantenbinding en het identificeren van high-value klanten.

## Workflow

1. **Data Voorbewerking:**  
   - Laden van datasets en omgaan met ontbrekende waarden  
   - Omzetten van datumvariabelen naar datetime-formaat  
   - Creëren van afgeleide features zoals tenure, recency, frequency en monetary value

2. **Exploratieve Data-analyse:**  
   - Basisstatistieken en visualisaties van klantgedrag  
   - Analyse van online/offline aankoopfrequentie en uitgavenpatronen

3. **KMeans Clustering:**  
   - Bepalen van het optimale aantal clusters met de Elbow-methode  
   - Clustering uitvoeren en segmentprofielen opstellen  
   - Identificeren van high-value, medium-value, dormant en potentiële klanten

4. **Hiërarchische Clustering:**  
   - Dendrogrammen visualiseren  
   - Clusters vormen met Ward- en average linkage methoden  
   - Detecteren van subgroepen en outliers

5. **Segmentanalyse:**  
   - Statistische analyse van elk cluster  
   - Overzicht van actieve, passieve en potentiële klanten  
   - Mogelijkheid om marketing- en win-back strategieën te bepalen

6. **Vergelijking van Methodes:**  
   - Cross-tabulation van KMeans en hiërarchische resultaten  
   - Evalueren van overlappingen en verschillen tussen methoden  
   - Bepalen van de meest bruikbare segmenten voor zakelijke beslissingen

## Visualisaties

- Dendrogrammen en Elbow plots  
- Kruistabellen van KMeans vs Hiërarchische clustering  
- Statistische overzichten van segmenten






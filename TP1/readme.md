
##  Pandas method 
* df.`head(n)` : affiche les $n$ premiérs  lignes 
    * df.`head(n)` : affiche par defaut  $5$  premiérs  lignes 
        

* df.`tail(n)` : affiche les $n$ derniéres  lignes 
    * df.`tail(n)` : affiche les $5$ derniéres  lignes 
* `movies_df.info()` : affiche  les colonne de notre Table movies_df 
* `movies_df.shape` : affiche nombre des lignes et le nombre de colonne 
* `movies_df.append(movies_df)` : duplique les données de table movies_df 
* `movies_df.drop_duplicates(inplace= True , keep =False)` : supprimer les données duplique
* `movies_df.columns` : affiche les colonnes de notre table movies_df 
* `movies_df.rename(columns={`
        `'Runtime (Minutes)': 'Runtime',` 
        `'Revenue (Millions)': 'Revenue_millions'`
    `}, inplace=True)` :  renommer certain colonne de table movies_df 

* `movies_df.columns =[]`:  change les colonnes de table movies_df 
* `movies_df.columns = [col.lower() for col in movies_df]`:  mettre tous les colonne en munisculle 
* `movies_df.isnull()`: affiche le contenu de table avec true si le cas est null si non False 
* `revenue.fillna(revenue_mean, inplace=True)`:  ajouter le colonne revenue_mean evec leur valeur a la fin de table revenue 
* `movies_df.isnull().sum()`: affiche somme des valeur null de chaque colonne 
* `movies_df.describe()`: applique sur tous les colonnes les fonctions suivants ( count , mean , std , min , 25% , 50% , 75% , max)

* `movies_df.dropna(axis=1)`: affiche le contenu de table sauf le premier colonne 
* `revenue = movies_df['revenue_millions']`:  affecter les données de colonne $revenue_millions$ vers le table revenue 
* `movies_df.describe()`: permet de calculer le  moyenne de table revenue 
* `revenue_mean = revenue.mean()`: permet de calculer le  moyenne de table revenue 
* `movies_df.sort_values(by='rank')`: trié  movies_df par le  rank  

* `movies_df.sort_index(1)`: Renvoie un nouveau DataFrame trié par étiquette si l'argument inplace est False, sinon met à jour le DataFrame d'origine et renvoie None.







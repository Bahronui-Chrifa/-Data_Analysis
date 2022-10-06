|commande  | description| 
|---------  | -----------| 
|`df.drop(______, axis=0 )`|supprimer une ligne | 
|`df.drop(______, axis=1 )`  | supprimer une ligne | 
|`df.rename(columns ={'__':'___' } , inplace= True `  | Renommer des colonnes   | 
|`df.cut(x , bins=[__,__,__] , labels=['___' ,'____','___']) `  | crée un colonne en atrubuer des label à chaque ligne  selon son intervalle  |  
|`df_ages = df_user_churn_cleaned.groupby('userid').max()`| On peur applique autres fonctions d'agrégations tel que`max() , min() , count() , mean()` , ... qui permet de sauvgarder un seul valeur qui satisfait le fonction appliquée  | 
|`datetime.now()`  |  Donner date systéme d'aujourd'hui     | 
|`df_user_churn_cleaned['col_name']=[_____].dt.days`  |  Ajouter colonne intutile col_name dans le table $df_user_churn_cleaned$  un valeur en nombre de jours     | 


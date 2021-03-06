﻿# Applications natives vs applications cross-platforms

![enter image description here](https://image.noelshack.com/fichiers/2019/15/3/1554889241-veilles.jpg)

Il existe deux types d'applications mobiles : les applications natives et les applications cross-platforms.

# **Applications natives**

Les applications natives sont des applications spécifiquement développées pour un système d'exploitation. Les systèmes d'exploitation les plus connus pour le mobile sont iOS et Android. Si vous souhaitez développer une application native et compatible avec iOS et Android, il faudra développer deux applications complètement différentes : une première pour iOS, en langage Swift ou Objective-C, et une seconde pour Android, en langage Kotlin ou Java. Pendant longtemps, et encore aujourd'hui, la grande majorité des applications mobiles réalisées étaient des applications natives.

![Das, sur iOS : Objective-C puis Swift. Sur Android : Java puis Kotlin](https://user.oc-static.com/upload/2018/03/31/15225081845661_native.png)sdddsg

# Inconvénients des applications native

![Image associée](http://oulhaj.com/img/private.png)

- Le principal inconvénient d’une application native est qu’elle doit respecter les règles définies par les différentes sociétés des plateformes mobiles tel que l'Apple Store ou Google Play.

- les conditions tarifaires imposées ou la non compatibilité avec les autres systèmes d’exploitation mobiles

- Le coût lié au développement d’une application native est un frein car généralement plus élevé si elle est portée sur plusieurs plateformes (afin d’être disponible pour un maximum d'utilisateurs

# Applications cross-platforms

Les applications cross-platforms, à l'inverse des applications natives, sont développées une seule et unique fois et sont compatibles sur iOS et Android. Le développement d'applications cross-platforms passe par des frameworks. Parmi les plus connus, on retrouve Ionic, PhoneGap, Xamarin et Titanium.

![https://user.oc-static.com/upload/2018/03/31/15225084240758_Untitled%20Diagram%20%285%29.png](https://user.oc-static.com/upload/2018/03/31/15225084240758_Untitled%20Diagram%20%285%29.png)

On ne développe pas une application cross-platform avec les _langages_ natifs, on utilise souvent des langages plus simples. Par exemple, Ionic / PhoneGap / Titanium fonctionnent avec du Javascript. Xamarin (produit de Microsoft) fonctionne avec du C#

# Inconvénients des applications cross-platforms

![Image associée](http://oulhaj.com/img/private.png)

Les applications cross-platforms sont réputées moins performantes et moins fluides que les applications natives. Souvent, les développeurs sont déçusEn réalité, il y a souvent des ajustements à faire pour chaque plateforme, ce qui rend votre projet de moins en moins clair et surtout de moins en moins unique On reproche également aux applications cross-platforms d'avoir un rendu visuel plus proche du web que du mobile.

# L'arrivée de React Native

![Logo React Native](https://user.oc-static.com/upload/2017/12/26/15142958404783_1_ypyKHfdnTbM-DZG-nZ5tRg.png)Alors que certains frameworks cross-platforms se contentent d'utiliser des composants web, React Native utilise les composants mobiles natifs. Cela signifie que, lorsque vous définissez par exemple une vue en React Native, sur iOS votre application affiche une `UIView` et sur Android une `android.view.View`, deux composants natifs.

- React Native est gratuit, du début de vos développements à la livraison de votre application mobile sur les stores.

- React Native est Open Source. Une grande communauté s'est ainsi construite autour du framework et a permis son accroissement.

- React Native permet de tester son application instantanément. Nous verrons ce point plus tard dans ce cours, mais cela facilite grandement les développements.

- Enfin, React Native est plus flexible . Il est tout à fait possible d'utiliser React Native dans un projet natif existant.

# Conclusion

Les deux technologies ne sont pas mauvaises elles ont toutes deux leursdéfauts et leurs qualités, le choix dépend surtout du développeur et de l'environnement qui lui convient le mieux.

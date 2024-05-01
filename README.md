# 8 kiálynő probléma dokumentáció - Mesterséges Intelligencia gyakorlat beadandó I. Kállai Viktor L88I9I

## Bevezetés

A "8 Királynő probléma" egy jól ismert számítógépes probléma, amely arra törekszik, hogy nyolc királynőt helyezzen el egy 8x8-as sakktáblán úgy, hogy egyik királynő se tudjon megtámadni egy másikat. A probléma megoldásához minden királynőnek külön sorban, oszlopban és átlóban kell lennie. A probléma egy lehetséges megoldása az, hogy minden sorban pontosan egy királynő legyen.

Ebben a dokumentációban két különböző algoritmust mutatok be a "8 Királynő probléma" megoldására: a backtracking és a hegymászó algoritmusokat.

## State osztály

A State osztály az összes lehetséges állapotot tartalmazza, amelyekben a probléma megoldása lehetséges. Minden állapotban egy 8x8-as sakktábla van, ahol a "Q" jelöli a királynőt, és a "." az üres mezőt.

## Operator osztály

Az operator osztály felelős az állapotok manipulálásáért. Az egyik operátor a királynő elhelyezését végzi el egy adott sorban és oszlopban a sakktáblán. A másik operátor a királynő eltávolítását végzi az adott pozícióból.

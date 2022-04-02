# Binary Search Tree
---
``
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]``
 **dizisinin Binary-Search-Tree aşamalarını yazınız.**
 #### Ör.
 >root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

 ## Cevap

**0 sayısını bulalım**

- **Aşama-1**      ``----------------[4]`` Root'umuz "4" olsun. 
</br>
- **Aşama-2**   ``---------[3]  ----------  [7]--------``
</br>
- **Aşama-3**   ``------[2]----[9]------[6]----[8]---``
</br>
- **Aşama-4**   ``--[1]--------------[5]-------------``
</br>
- **Aşama-4** ``[0]--------------------------------``

---
### Yazıyla'

>3<4 o zaman sola yazıyoruz, 7>4 sağa yazıyoruz.
>2<3 o zaman sola yazıyoruz, 6<7 sola yazıyoruz.
>9>3 o zaman sağa yazıyoruz, 8>7 sağa yazıyoruz.
>1<2 o zaman sola yazıyoruz, 5<6 sola yazıyoruz.
>0<1 o zaman sola yazıyoruz ve tamamlıyoruz.

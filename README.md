��#   W e L o v e M o v i e s   -     T h i n k f u l   C a p t s t o n e  
  
 B u i l t   u s i n g   E x p r e s s ,   K n e x ,   a n d   P o s t g r e S Q L  
  
 # #   T o   r u n   t h e   s e r v e r  
  
 1 .   F o r k / C l o n e   t h i s   r e p o s i t o r y  
 2 .   ` c d `   i n t o   t h e   p r o j e c t   d i r e c t o r y  
 3 .   R u n   ` n p m   i n s t a l l `   t o   i n s t a l l   p r o j e c t   d e p e n d e n c i e s  
 4 .   R u n   ` n p m   r u n   s t a r t : d e v `   t p   s t a r t   s e r v e r   i n   d e v e l o p m e n t   m o d e  
 5 .   O R   r u n   ` n p m   s t a r t `  
  
 # #   O b j e c t i v e s  
 T h i s   p r o j e c t   i s   d e s i g n e d   t o   t e s t   y o u r   a b i l i t y   t o   b u i l d   c o m p l e x   s e r v e r s   a n d   a c c e s s   d a t a   t h r o u g h   a   d a t a b a s e .   T o   s u c c e e d ,   d e m o n s t r a t e   t h e   f o l l o w i n g   t a s k s :  
  
 *   I n s t a l l   a n d   u s e   c o m m o n   m i d d l e w a r e   p a c k a g e s  
 *   R e c e i v e   r e q u e s t s   t h r o u g h   r o u t e s  
 *   R u n   t e s t s   f r o m   t h e   c o m m a n d   l i n e  
 *   A c c e s s   r e l e v a n t   i n f o r m a t i o n   t h r o u g h   r o u t e   a n d   q u e r y   p a r a m e t e r s  
 *   C r e a t e   a n   e r r o r   h a n d l e r   f o r   t h e   c a s e   w h e r e   a   r o u t e   d o e s n ' t   e x i s t  
 *   B u i l d   a n   A P I   f o l l o w i n g   R E S T f u l   d e s i g n   p r i n c i p l e s  
 *   C r e a t e   a n d   c u s t o m i z e   a   k n e x f i l e . j s   f i l e  
 *   C r e a t e   a   c o n n e c t i o n   t o   y o u r   d a t a b a s e   w i t h   K n e x  
 *   W r i t e   d a t a b a s e   q u e r i e s   t o   c o m p l e t e   C R U D   r o u t e s   i n   a n   E x p r e s s   s e r v e r  
 *   R e t u r n   j o i n e d   a n d   n e s t e d   d a t a   w i t h   K n e x  
 *   W r i t e   d a t a b a s e   m i g r a t i o n s   u s i n g   K n e x ' s   m i g r a t i o n   t o o l  
 *   D e p l o y   y o u r   b a c k e n d   s e r v e r   t o   a   c l o u d   s e r v i c e  
  
 # #   G e n e r a l   T a s k s  
 A l s o   w i l l   n e e d   t o   m a k e   s u r e   t h e   f o l l o w i n g   t a s k s   a r e   c o m p l e t e  
  
 *   Y o u r   a p p . j s   f i l e   a n d   s e r v e r . j s   f i l e   a r e   c o r r e c t l y   c o n f i g u r e d ,   w i t h   y o u r   a p p . j s   f i l e   e x p o r t i n g   t h e   a p p l i c a t i o n   c r e a t e d   f r o m   E x p r e s s .  
 *   Y o u   u s e   t h e   c o r s   p a c k a g e   s o   t h a t   r e q u e s t s   f r o m   t h e   f r o n t e n d   c a n   c o r r e c t l y   r e a c h   t h e   b a c k e n d .  
 *   I f   a   r e q u e s t   i s   m a d e   t o   a   r o u t e   t h a t   d o e s n ' t   e x i s t ,   t h e   s e r v e r   r e t u r n s   a   4 0 4   e r r o r .  
 *   I f   a   r e q u e s t   i s   m a d e   t o   a   r o u t e   t h a t   e x i s t s   b u t   t h e   H T T P   m e t h o d   i s   w r o n g ,   t h e   s e r v e r   r e t u r n s   a   4 0 5   e r r o r .  
 *   A l l   o f   y o u r   r o u t e s   r e s p o n d   w i t h   t h e   a p p r o p r i a t e   s t a t u s   c o d e   a n d   u s e   a   d a t a   k e y   i n   t h e   r e s p o n s e . # Movies_Backend

��#   S w a s t i k   i s   b a s i c a l l y ,   a   H e a l t h   &   N u t r i t i o n   M o n i t o r i n g   S e r v i c e   A p p l i c a t i o n   f o r   t h e   c a u s e   o f   W o m e n   a n d   c h i l d   n u t r i t i o n ,  
 B u t   i t   c a n   b e   u s e d   f o r   u s e d   f o r   v a r i o u s   o t h e r   p u r p o s e s . < b r   / >  
  
 T h i s   i s   S w a s t i k   A P I   a n d   r o u t e s ,   t h a t   h a n d l e s   a l l   t h e   c o n n e c t i o n s   t o   t h e   d a t a b a s e . < b r   / >  
  
  
 < p r e >  
 R E S T f u l   R o u t i n g :  
  
 A )           F u n c t i o n i n g   o f   t h e   R o u t e                                                                                     R e q u e s t   T y p e                                         U R L  
  
 1 . T o   L o g i n   t h e   a d m i n   p o r t a l   u s e r   i n t o   s w a s t i k   I n t e r f a c e                                     G E T   R e q u e s t                   h t t p s : / / d o m a i n _ n a m e / L o g i n  
  
 2 . T o   R e g i s t e r   t h e   u s e r   o n t o   t h e   d a t a b a s e                                                                   G E T   R e q u e s t                   h t t p s : / / d o m a i n _ n a m e / S i g n u p  
  
 3 . T o   L o g o u t   t h e   u s e r   f r o m   t h e   c u r r e n t   s e s s i o n                                                         G E T   R e q u e s t                   h t t p s : / / d o m a i n _ n a m e / L o g o u t  
  
 4 . T o   R e n d e r   t h e   r e g i s t e r   p a r e n t   f o r m                                                                           G E T   R e q u e s t                   h t t p s : / / d o m a i n _ n a m e / R e g i s t e r / p a r e n t  
  
 5 . T o   R e g i s t e r   t h e   p a r e n t .                                                                                                 P O S T   R e q u e s t                 h t t p s : / / d o m a i n _ n a m e / R e g i s t e r / p a r e n t  
  
 6 . T o   R e n d e r   t h e   r e g i s t e r   c h i l d   f o r m                                                                             G E T   R e q u e s t                   h t t p s : / / d o m a i n _ n a m e / R e g i s t e r / c h i l d  
  
 7 . T o   R e g i s t e r   t h e   c h i l d .                                                                                                   P O S T   R e q u e s t                 h t t p s : / / d o m a i n _ n a m e / R e g i s t e r / c h i l d  
  
 8 . T o   g e t   t h e   d e t a i l s   o f   t h e   p a r e n t   w i t h   t h e   a a d h a r   n o .                                       P O S T   R e q u e s t                 h t t p s : / / d o m a i n _ n a m e / C l i e n t / p a r e n t  
  
 9 . T o   g e t   t h e   d e t a i l s   o f   t h e   c h i l d r e n   o f   t h e   p a r e n t   p r e s e n t .                             G E T   R e q u e s t                   h t t p s : / / d o m a i n _ n a m e / C l i e n t / p a r e n t / : a a d h a r n o / c h i l d r e n  
  
 1 0 .   T o   u p d a t e   t h e   d e t a i l s   o f   a n y   c h i l d r e n   w i t h   I D                                                 P U T   R e q u e s t                   h t t p s : / / d o m a i n _ n a m e / C l i e n t / c h i l d r e n / : c h i l d _ i d / u p d a t e  
  
 1 1 .   T o   s e n d   a n y   t y p e   o f   m e s s a g e   t o   a n   a r r a y   o f   n u m b e r s                                       P O S T   R e q u e s t                 h t t p s : / / d o m a i n _ n a m e / M e s s a g e / s e n d t o a l l  
  
 1 2 .   G e t   p h o n e n o s   o f   p a r e n t s   w h o s e   w a r d   v a c c i n a t i o n   d a t e   i s   c l o s e                   G E T   R e q u e s t                 h t t p s : / / d o m a i n _ n a m e / M e s s a g e / p h o n e n o s  
  
 1 3 .   G e t   e m a i l s   o f   p a r e n t s   w h o s e   w a r d   v a c c i n a t i o n   d a t e   i s   c l o s e                       G E T   R e q u e s t                 h t t p s : / / d o m a i n _ n a m e / M e s s a g e / e m a i l  
  
 1 4 .   S a m p l e   p r o t e c t e d   r o u t e   f o r   a u t h   v e r i f i c a t i o n                                                   G E T   R e q u e s t                 h t t p s : / / d o m a i n _ n a m e / P r o t e c t e d  
  
 1 5 .   G e t   t h e   c o u n t   o f   p a t i e n t s   o f   a l l   d i s e a s e   c a t e g o r i s e d   a s   a   m a p .               G E T   R e q u e s t                 h t t p s : / / d o m a i n _ n a m e / s t a t i s t i c s / p a t i e n t s _ c o u n t _ w r t _ d i s e a s e  
  
 1 6 .   G e t   t h e   c o u n t   o f   c h i l d r e n   c a t e g o r i s e d   o n   b a s i s   o f   p i n c o d e                         G E T   R e q u e s t                 h t t p s : / / d o m a i n _ n a m e / s t a t i s t i c s / c h i l d r e n / p i n c o d e  
  
 1 7 .   G e t   t h e   J S O N   a r r a y   o f   c h i l d r e n   c a t e g o r i s e d   o n   b a s i s   o f   p i n c o d e               G E T   R e q u e s t                 h t t p s : / / d o m a i n _ n a m e / s t a t i s t i c s / c h i l d r e n / p i n c o d e / : p i n c o d e  
  
 1 8 .   A l l o w s   m e s s a g i n g   t o   a l l   p a r e n t s   w h o s e   w a r d   l i v e   i n   a   u n i q u e   p i n c o d e     G E T   R e q u e s t                 h t t p s : / / d o m a i n _ n a m e / m e s s a g e / p h o n e n o s / a l l _ p a r e n t s / : p i n c o d e  
  
 1 9 .   A l l o w s   t o   r e g i s t e r   c o m p l a i n t ,   a c c e p t s   e m a i l   a n d   c o m p l a i n   a s   f e i l d s       P O S T   R e q u e s t               h t t p s : / / d o m a i n _ n a m e / c o m p l a i n / l o g _ c o m p l a i n t  
  
 2 0 .   R e t u r n s   t h e   c o u n t   o f   m a l e   a n d   f e m a l e   p a r e n t s   a s   w e l l   a s   c h i l d r e n           G E T   R e q u e s t                 h t t p s : / / d o m a i n _ n a m e / s e a r c h / c o u n t _ p a r e n t s _ c h i l d r e n  
  
 S o ,   T h e s e   2 0   r o u t e s   c a n   h a n d l e   a n y   o p e r a t i o n   f r o m   o r   o n   t h e   d a t a b a s e .  
  
 T h i s   i s   n o t   a n   o p e n   s o u r c e   A P I ,   a n d   i t ' s   �   c o p y r i g h t   a r e   r e s e r v e d   s o l e l y   w i t h   t h e   c r e a t o r .      
 < / p r e > "# hack5.0_server" 

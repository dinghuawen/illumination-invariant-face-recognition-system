<h1>Illumination Invariant Face Recognition System</h1>
<i><p>Illumination Invariant Face Recognition is a face recognition system able to recognize human face under different illumination conditions.<br>
</p>
</i>
<h1>Introduction</h1>
<p>
A face recognition usually suffers difficulty while recognition faces under different illumination condition.so, face image must be illumination normalized to get normalized face image which helps in the extraction of illumination invariant face features when used together with face recognition algorithms.Among Several illumination normalization algorithms available, the system described here uses Single Scale Self Quotient Image. The face is recognized using Principal Component Analysis and Regularized Linear Discriminant Analysis. A combined Decision is made by two different algorithms.Both PCA and regularized LDA help in the determination of best matching human face used in the training with the new input face image. There is always a problem for rejecting face of the person not involved while training.  PCA features is combined with Learning Vector Quantization (LVQ) which is used as a standard approach to reject the unknown faces not known to the system. All these faces are rejected by the system and only those known faces that system is trained for is accepted.<br>
</p>
<a href='http://s380.photobucket.com/albums/oo244/swastikrules/?action=view&amp;current=IIFR.jpg'><img src='http://i380.photobucket.com/albums/oo244/swastikrules/IIFR.jpg' alt='Photobucket' border='0' /></a>
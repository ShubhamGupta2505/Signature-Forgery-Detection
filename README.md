# Signature Forgery Detection
### Details of folder is as follows -
- Signature-Forgery.ipynb file contains model
- Forged Images contain dataset for this project in form of real 
- Real Images contain dataset for this project in form of real 
- "training folder" will save the trained images(this folder will create when you will execute the code)

### Some Important points
- Images are stored in the format : XXXZZZ_YYY
- XXX denotes id of the person who has signed on the document(ex -001)
- ZZZ denotes the id of the person to whom the sign belongs in actual(ex- 001)
- YYY deontes the n'th no.of attempt
- Now if XXX == ZZZ then image is genuine otherwise the signature is forged

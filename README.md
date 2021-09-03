# OnePageChess
An entire chess game you can play (where you enforce the rules) using only one html file. No other dependencies.

# Quick Start
[Here's a video link to Greg Young explaining the app. Greg wanted me to add FEN notation to the URI.](https://vimeo.com/597281686)

## Operation

1. Load the file either from a local drive or a website
2. Move pieces as you will. Click piece then click where you want it to go
3. To delete a piece, click it then hit the "delete" key
4. You can change who-goes-next, Black Player name, White Player name, location-year, and add comments
5. To change these items, simply click in the area and edit, as you leave, changes are made to the URL
6. When you have the board the way you want, copy the URL. Mail, text, etc the link.

## Examples

1. Download the chessboard.html file from here. Open it in your browser

- Add this onto the end of the filename like so:

```
chessboard.html?b=Ra1%2CPa2%2Cpa7%2Cra8%2CPb2%2Cpb6%2Cbb7%2Cnb8%2CPc2%2Cpc7%2CPd4%2Cpd7%2CKe1%2CBe2%2Cpe6%2CQe7%2CPf2%2CNf6%2Crf8%2Ckg2%2CPg3%2CNg4%2Cpg7%2CRh1%2CPh4&g=w&p=Thomas%2CLasker&l=London%2C+1912%0A&c=White+mates+in+two+moves%0A
```

2. Access the page from the net.

[Here's the file on one of my S3 buckets](http://cdn.danielbmarkham.com/chessboard.html)

[Here's The Mexican Immortal game using that S3 file](http://cdn.danielbmarkham.com/chessboard.html?b=Pa2%2Cpa7%2Cra8%2CPb4%2Cqb5%2Cbb7%2CPd4%2Cpd6%2CRe1%2CNe3%2Cpe6%2Cre8%2CPf2%2Cpf7%2Cnf8%2CKg1%2CPg2%2CRg3%2CBg5%2Cpg7%2Ckg8%2CPh2%2CQh5%2Cph6&g=w&p=Torre%2CLasker&l=Moscow%2C+1925%0A&c=The+Mexican+Immortal+aka+%22Seventh+Seal%22%0A)

**Note load times!** Usually the entire file caches up and is instantaneously available on next use.

## Known Bugs

(Developed and tested in FF Nightly. YMMV in other browsers.)

- If you select a piece, then go to edit one of the fields, then hit delete, it will both delete text and delete the selected piece


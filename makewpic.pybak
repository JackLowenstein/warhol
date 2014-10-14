def makeWpic():
  fname = pickAFile()
  pic = makePicture(fname)
  newPic = shrink(pic)
  wPic = makeEmptyPicture)getWidth(pic), getHeight(pic))
  copyinto(newPick, wPic, 0 , 0)
  show(wPic)
  
def shrink():
  newPic = makeEmptyPicture(w(pic)/2,h(pic)/2)
  for col in range (0, width(pic), 2):
    for row in range (0, getHeight(pic), 2):
      ps = getPixel(pic, col, row)
      pd = getPixel(newPic, col/2, row/2)
      getColor(pd, getColor(ps))
   return newPic
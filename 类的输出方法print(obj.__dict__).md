# learningLog
python learning

  1 class OpaqueClass(object):
  2     def __init__(self,x,y):
  3         self.x=x
  4         self.y=y
  5     def __repr__(self):
  6         return 'BetterClass(%d,%d)'%(self.x,self.y)
  7 obj=OpaqueClass(1,2)
  8 #print(obj.__dict___)
  9 print(obj)

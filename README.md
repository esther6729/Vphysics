# -*- coding: utf8 -*-
# 匯入視覺化套件
from visual import *

#產生一個寬400像素，高400像素的3度空間以進行繪圖
scene = display(width=400, height=400)
#產生一個扁長形方塊，當做是地板
floor = box(pos=(0,0,0), length=0.3, height=0.005, width=0.1)

from building import *
import os

cwd     = GetCurrentDir()
group   = []
CPPPATH = [cwd]

src = Glob('*.cpp')

group = group + DefineGroup('at24c256', src, depend = ['PKG_USING_ARDUINO_AT24C256'], CPPPATH = CPPPATH)

Return('group')
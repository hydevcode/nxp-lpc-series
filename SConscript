import os
from building import *

objs = []
cwd  = GetCurrentDir()

if GetDepend(['SOC_LPC54608']):
    objs = objs + SConscript('lpc54608/SConscript')

if GetDepend(['SOC_LPC54114']):
    objs = objs + SConscript('lpc54114/SConscript')

if GetDepend(['SOC_LPC5410']):
    objs = objs + SConscript('lpc5410x/SConscript')

if GetDepend(['SOC_LPC824']):
    objs = objs + SConscript('lpc824/SConscript')

if GetDepend(['SOC_LPC4088']):
    objs = objs + SConscript('lpc408x/SConscript')

if GetDepend(['SOC_LPC178X']):
    objs = objs + SConscript('lpc178x/SConscript')

if GetDepend(['SOC_LPC176']):
    objs = objs + SConscript('lpc176x/SConscript')

Return('objs')

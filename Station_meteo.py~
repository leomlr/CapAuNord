"""

Auteur: Léo Meillier
Interface: microbit
Nom du projet: OpenLog
Description: No-description
Toolbox: vittascience
Mode: mixed
Blocks: <xml xmlns="https://developers.google.com/blockly/xml"><variables><variable id="12-xGMT@Yf)||7FMbS^c">data</variable><variable id="3_70vJJuBBoUunLvY:=o">text</variable><variable id="wIHo|c%rzRM?xEO[?=Y4">HEADER</variable><variable id="YMgC_dAi08q]Flc@B$PQ">HEADER_UNIT</variable></variables><block type="on_start" id="G[=T#8yqB70`NFgYq}GP" deletable="false" x="-338" y="137"><statement name="DO"><block type="procedures_callnoreturn" id="g=;Hdq~*ePY9q5n7}n[@"><mutation name="printConsole"><arg name="data"></arg></mutation><value name="ARG0"><block type="text" id="LtK%VtPbGWB7*p]/^1PZ"><field name="TEXT">Initialisation du module RTC au 06/08/2022 à 12h50'10</field></block></value><next><block type="communication_clockRTC_setDate" id="^upsl3j}}pyWq[hG)ogu"><field name="MODULE">PCF85063TP</field><field name="DAY">WED</field><field name="DATE">2022-06-08</field><next><block type="communication_clockRTC_setHour" id="|o?mccj;|V,T_imxX($H"><field name="MODULE">PCF85063TP</field><value name="HOUR"><shadow type="math_number" id="]_dx7(b=pFA#=Uw*To6q"><field name="NUM">13</field></shadow></value><value name="MIN"><shadow type="math_number" id="wpGuu)y#@gG+YR$js$a@"><field name="NUM">10</field></shadow></value><value name="SEC"><shadow type="math_number" id="^*Opp{1N)9$RJHQ`_TFL"><field name="NUM">10</field></shadow></value><next><block type="procedures_callnoreturn" id="jz%|qmxCd2YHhq9r=L?#"><mutation name="printConsole"><arg name="data"></arg></mutation><value name="ARG0"><block type="text" id="D?@~fq{xxm);7bVU$-[j"><field name="TEXT">Attente de 2 secondes ...</field></block></value><next><block type="io_pause" id="pf%mK*K!xdN;(=2Mq+l~"><field name="UNIT">SECOND</field><value name="TIME"><shadow type="math_number" id="KBN3JkN#bl}Im{e:f;?/"><field name="NUM">2</field></shadow></value><next><block type="procedures_callnoreturn" id="fBZMBt;~0|[WH!kNSiq="><mutation name="printConsole"><arg name="data"></arg></mutation><value name="ARG0"><block type="text" id="1Yy:H4pvAIbCIVRT;p_g"><field name="TEXT">Lecture du module RTC:</field></block></value><next><block type="procedures_callnoreturn" id="vu-qC6koz17Sk0V_D$S["><mutation name="printConsole"><arg name="data"></arg></mutation><value name="ARG0"><block type="communication_clockRTC_readTime" id=")/_H[Ry}xlsp)BMw[o)~"><field name="MODULE">PCF85063TP</field><field name="DATA">ALL</field></block></value><next><block type="procedures_callnoreturn" id="LqaHgmDyQ~2Sr*dzUf#="><mutation name="printConsole"><arg name="data"></arg></mutation><value name="ARG0"><block type="text" id="R7GHQnw4{ENmBid4Yk8o"><field name="TEXT">Ecriture de l'enttête dans la carte SD </field></block></value><next><block type="procedures_callnoreturn" id="*2DEwPdFaQsZp)NeWaC,"><mutation name="saveData"><arg name="data"></arg></mutation><value name="ARG0"><block type="text_join" id="b8b:m7DUa_?/5l`/#GwH"><mutation items="4"></mutation><value name="ADD0"><block type="text_newline" id="Ll^h,;.X)1abra67/Min"><value name="N"><shadow type="math_number" id="D7L8pB?8SsrW#C~Y@dS."><field name="NUM">1</field></shadow></value></block></value><value name="ADD1"><block type="text" id="g2x]Id|F]O/%qnGibh@;"><field name="TEXT">Enregistrement de données le </field></block></value><value name="ADD2"><block type="communication_clockRTC_readTime" id="7$7~UhwyqJ}Es7HJ07t6"><field name="MODULE">PCF85063TP</field><field name="DATA">ALL</field></block></value><value name="ADD3"><block type="text_newline" id="8Fc~@~H5WQ__pbD7;/b7"><value name="N"><shadow type="math_number" id="t*=DDdFWgeJ,ba3g=.J~"><field name="NUM">1</field></shadow></value></block></value></block></value><next><block type="variables_set" id="R7BWS`V2s0F/NiG2pcdE"><field name="VAR" id="wIHo|c%rzRM?xEO[?=Y4">HEADER</field><value name="VALUE"><shadow type="math_number" id="!0.rY=JxZR1G7q~pPe^L"><field name="NUM">0</field></shadow><block type="text_join" id="O](aqzO%qE.rY`*#PEy3"><mutation items="13"></mutation><value name="ADD0"><block type="text" id="VLM.G5*UPMn`gB=kP.k:"><field name="TEXT">t</field></block></value><value name="ADD1"><block type="text" id="1WoWO%43Gayg.TL!0TOF"><field name="TEXT">;</field></block></value><value name="ADD2"><block type="text" id="}6pv5SyqMn$}URe4Z^=o"><field name="TEXT">Vitesse du vent</field></block></value><value name="ADD3"><block type="text" id="a7)EyWH*MUqeQx:=o$0D"><field name="TEXT">;</field></block></value><value name="ADD4"><block type="text" id="K`[V`$O1Mn[$%Q4Ty~po"><field name="TEXT">Direction du vent</field></block></value><value name="ADD5"><block type="text" id="`$/:JqpR}%{;Znuka95Q"><field name="TEXT">;</field></block></value><value name="ADD6"><block type="text" id="$i|ri=EV~5A{-muc`|j*"><field name="TEXT">Température</field></block></value><value name="ADD7"><block type="text" id="ARwbHjN!CId_u.FCW/(/"><field name="TEXT">;</field></block></value><value name="ADD8"><block type="text" id="djE(Tl/XlzvjB/(3N.Db"><field name="TEXT">Humidité</field></block></value><value name="ADD9"><block type="text" id="};Q0+}JyUr6V)%;^I0/*"><field name="TEXT">;</field></block></value><value name="ADD10"><block type="text" id="Vh`eWD4P$_DM,lyb;6#}"><field name="TEXT">Altitude</field></block></value><value name="ADD11"><block type="text" id="jI.nLTVGffki./4LzUO;"><field name="TEXT">;</field></block></value><value name="ADD12"><block type="text" id="rJ^hhBs!_wywCP}}?L22"><field name="TEXT">Pression</field></block></value></block></value><next><block type="procedures_callnoreturn" id="f);N%Wcx%[1$H@mQHYgM"><mutation name="printConsole"><arg name="data"></arg></mutation><value name="ARG0"><block type="variables_get" id="ERz@koIP3Pp?Z;}(Xh;m"><field name="VAR" id="wIHo|c%rzRM?xEO[?=Y4">HEADER</field></block></value><next><block type="procedures_callnoreturn" id="WswM0hXGoNZ_2+Ana!y$"><mutation name="saveData"><arg name="data"></arg></mutation><value name="ARG0"><block type="variables_get" id="+]9_[q4A|B(#;UPlE($-"><field name="VAR" id="wIHo|c%rzRM?xEO[?=Y4">HEADER</field></block></value><next><block type="variables_set" id="wf1Aq^5uw1~?55(*):DD"><field name="VAR" id="YMgC_dAi08q]Flc@B$PQ">HEADER_UNIT</field><value name="VALUE"><shadow type="math_number" id="`qYtI7D#bWvzFh6VTkU`"><field name="NUM">0</field></shadow><block type="text_join" id="a]5.cDv|iM#y`-~cM]c6"><mutation items="14"></mutation><value name="ADD0"><block type="text" id="N/BufKg^0zEE_Thsz:y/"><field name="TEXT">s</field></block></value><value name="ADD1"><block type="text" id="147}I4!t,ssgL9e1]v3."><field name="TEXT">;</field></block></value><value name="ADD2"><block type="text" id="$SBKCgGU%ezRNA#sczk1"><field name="TEXT">m/s</field></block></value><value name="ADD3"><block type="text" id=":BNiP-i1DSI,Qft/d2K)"><field name="TEXT">;</field></block></value><value name="ADD4"><block type="text" id="c%.vr(J%sH}8~2fW8nI:"><field name="TEXT">Dir</field></block></value><value name="ADD5"><block type="text" id="{RTxEPC#lBjK*K9nP,c}"><field name="TEXT">;</field></block></value><value name="ADD6"><block type="text" id="x.*2j-syfM4n:6~Ec$ky"><field name="TEXT">°C</field></block></value><value name="ADD7"><block type="text" id="x9Q}w2eg8GE?ihNU?67l"><field name="TEXT">;</field></block></value><value name="ADD8"><block type="text" id="L5(5qYx%MeCg%#W@0zFd"><field name="TEXT">%</field></block></value><value name="ADD9"><block type="text" id="lH16%Emj]k~vk`JA^CiB"><field name="TEXT">;</field></block></value><value name="ADD10"><block type="text" id="xaV,T.,7feaH{~!r7+p~"><field name="TEXT">m</field></block></value><value name="ADD11"><block type="text" id="?N/dK0OEx3(;RqFe!Nw|"><field name="TEXT">;</field></block></value><value name="ADD12"><block type="text" id="G*86^Iv7YkD$~q(]90Ol"><field name="TEXT">hPa</field></block></value><value name="ADD13"><block type="text_newline" id="W(BWph76PZT)EEcLWg:o"><value name="N"><shadow type="math_number" id=")Mz@cEwX%/tlm{[NZPgl"><field name="NUM">1</field></shadow></value></block></value></block></value><next><block type="procedures_callnoreturn" id="d4rqoZp4DKfz1unLIkaW"><mutation name="printConsole"><arg name="data"></arg></mutation><value name="ARG0"><block type="text_join" id="t:amKa:{|VdMexARHS63"><mutation items="2"></mutation><value name="ADD0"><block type="variables_get" id="7x1Ausoc.E=a*$6|OEzU"><field name="VAR" id="YMgC_dAi08q]Flc@B$PQ">HEADER_UNIT</field></block></value><value name="ADD1"><block type="text_newline" id="~G6e76Npu#)|*WYknnCB"><value name="N"><shadow type="math_number" id="mVlf68H*#~4u:,Cma((o"><field name="NUM">1</field></shadow></value></block></value></block></value><next><block type="procedures_callnoreturn" id="I]JI+j@W02iit@,+Uq=H"><mutation name="saveData"><arg name="data"></arg></mutation><value name="ARG0"><block type="variables_get" id="4B@_S{]*Z;xL::kM6-]V"><field name="VAR" id="YMgC_dAi08q]Flc@B$PQ">HEADER_UNIT</field></block></value><next><block type="procedures_callnoreturn" id="J4]}.|R_kFkzv%yM):bV"><mutation name="printConsole"><arg name="data"></arg></mutation><value name="ARG0"><block type="text" id="JDX#|2-TrzRywn^MtB6E"><field name="TEXT">Attente de 2 secondes ...</field></block></value><next><block type="io_pause" id="yWMbt})2ps$T}qh1$dg5"><field name="UNIT">SECOND</field><value name="TIME"><shadow type="math_number" id="zR3~H@6|LIs|xiS%CUEm"><field name="NUM">2</field></shadow></value></block></next></block></next></block></next></block></next></block></next></block></next></block></next></block></next></block></next></block></next></block></next></block></next></block></next></block></next></block></next></block></next></block></statement></block><block type="procedures_defnoreturn" id="?c)uk$8JPAEXc(I,Xs9%" x="488" y="163"><mutation name="printConsole"><arg name="data" varid="12-xGMT@Yf)||7FMbS^c" paramId="=B.z]dTKaWaWNA+izl3r"></arg></mutation><field name="NAME">printConsole</field><field name="=B.z]dTKaWaWNA+izl3r">text</field><statement name="STACK"><block type="communication_serialRedirectUSB" id="n9U{s.,SpRXQB[R4+3ml"><next><block type="communication_serialWrite" id=",@)fL+oK*Bbz0$N~=G:W"><mutation newlines="false"></mutation><value name="TEXT"><shadow type="text" id=".-2:a/v6zH:WN6.@18JI"><field name="TEXT">Lecture du module RTC:</field></shadow><block type="variables_get" id="`]w+NWJ5.G*on?7t9^lb"><field name="VAR" id="3_70vJJuBBoUunLvY:=o">text</field></block></value></block></next></block></statement></block><block type="procedures_defnoreturn" id="spg3NXawb.{7H_ltnsxY" x="488" y="463"><mutation name="saveData"><arg name="data" varid="12-xGMT@Yf)||7FMbS^c" paramId="=B.z]dTKaWaWNA+izl3r"></arg></mutation><field name="NAME">saveData</field><field name="=B.z]dTKaWaWNA+izl3r">data</field><statement name="STACK"><block type="communication_writeOpenLogSd" id="BwZ6)SF=qYY0n]x+DNLp"><field name="BAUD">57600</field><field name="TX">pin15</field><field name="RX">pin14</field><value name="DATA"><block type="variables_get" id="pwxt|MH?o.y*P)E$s9{f"><field name="VAR" id="12-xGMT@Yf)||7FMbS^c">data</field></block></value></block></statement></block><block type="forever" id="o[WN]+eeF.OUxGch67@8" x="487" y="1062"><statement name="DO"><block type="variables_set" id="TFrWt1=^4!9,/P@Ne1$["><field name="VAR" id="12-xGMT@Yf)||7FMbS^c">data</field><value name="VALUE"><shadow type="math_number" id="xEA;/$c[t7OeEW$7_B7!"><field name="NUM">0</field></shadow><block type="text_join" id="9tr5;ru(;ZDHBS09x0~2" inline="false"><mutation items="13"></mutation><value name="ADD0"><block type="text_join" id="oPD]71+?bn{y)I6WOhm2" inline="false"><mutation items="5"></mutation><value name="ADD0"><block type="communication_clockRTC_readTime" id="PN~Oq0CP^ZZl/)}ft-[V"><field name="MODULE">PCF85063TP</field><field name="DATA">4</field></block></value><value name="ADD1"><block type="text" id=")-NMZO)M{U+arwWTr3yU"><field name="TEXT">:</field></block></value><value name="ADD2"><block type="communication_clockRTC_readTime" id="W_f.Sf@+4OjyMbph-E/j"><field name="MODULE">PCF85063TP</field><field name="DATA">5</field></block></value><value name="ADD3"><block type="text" id="%WxQ5L1~ix5@)SN8}tYd"><field name="TEXT">:</field></block></value><value name="ADD4"><block type="communication_clockRTC_readTime" id="#OZW~{,N6ZQXI;Wzm?i5"><field name="MODULE">PCF85063TP</field><field name="DATA">6</field></block></value></block></value><value name="ADD1"><block type="text" id="cJ9aR7z759:Uu|[.IlTe"><field name="TEXT">;</field></block></value><value name="ADD2"><block type="sensors_weatherbit_anemometer_getSpeed" id="kRM6zCh(VipN0ld)jzrc"><field name="UNIT">M_S</field></block></value><value name="ADD3"><block type="text" id="#aFYb-/i7yC.r$.w4^X%"><field name="TEXT">;</field></block></value><value name="ADD4"><block type="sensors_weatherbit_weathercock_getDirection" id="tHMA$aH^@DB-^=IOf=GY"></block></value><value name="ADD5"><block type="text" id="M:*hNzkQgsM|(Zl{0hXL"><field name="TEXT">;</field></block></value><value name="ADD6"><block type="sensors_weatherbit_bme280_getData" id="pnU!cRqW}:dnkp!y1D=R"><mutation temp="true"></mutation><field name="DATA">TEMP</field><field name="UNIT">CELSIUS</field></block></value><value name="ADD7"><block type="text" id="K%p@j/#9|r}e{?i~9fDL"><field name="TEXT">;</field></block></value><value name="ADD8"><block type="sensors_weatherbit_bme280_getData" id="rZkJ|QLRld((64a+D76H"><mutation temp="false"></mutation><field name="DATA">HUM</field></block></value><value name="ADD9"><block type="text" id="H}RB(:V!l):8qj._uV6-"><field name="TEXT">;</field></block></value><value name="ADD10"><block type="sensors_weatherbit_bme280_getData" id="W6@UG$gcraJ*$nhm}e-M"><mutation temp="false"></mutation><field name="DATA">ALT</field></block></value><value name="ADD11"><block type="text" id="/GdKj{@I3rv6.F;ndj;n"><field name="TEXT">;</field></block></value><value name="ADD12"><block type="sensors_weatherbit_bme280_getData" id="BkAfS{*c^PsDi7Ilh~C;"><mutation temp="false"></mutation><field name="DATA">PRESS</field></block></value></block></value><next><block type="procedures_callnoreturn" id="qbRf;f(wl^g0GT/H~.?p"><mutation name="printConsole"><arg name="data"></arg></mutation><value name="ARG0"><block type="text" id="{IAYc1-u!-fr8^|aiD1C"><field name="TEXT">Nouvel enregistrement:</field></block></value><next><block type="procedures_callnoreturn" id="]th1~rk-PT[h#ArF6b~M"><mutation name="printConsole"><arg name="data"></arg></mutation><value name="ARG0"><block type="variables_get" id="H~c9cd`S9VbGx-gB6B#x"><field name="VAR" id="12-xGMT@Yf)||7FMbS^c">data</field></block></value><next><block type="procedures_callnoreturn" id="/tS:Il}y~N6Qx(VSNX7D"><mutation name="saveData"><arg name="data"></arg></mutation><value name="ARG0"><block type="variables_get" id="IgZhd#~u.thj)ju]z+]2"><field name="VAR" id="12-xGMT@Yf)||7FMbS^c">data</field></block></value><next><block type="io_pause" id="~0QM)[x0olg[.;aO%W_8"><field name="UNIT">SECOND</field><value name="TIME"><shadow type="math_number" id="OvBo;kN)QsOmvQ6-$[]x"><field name="NUM">1</field></shadow></value></block></next></block></next></block></next></block></next></block></statement></block></xml>

Projet généré par Vittascience.

Ce fichier contient le code textuel ainsi que le code blocs. Il peut être importé de nouveau
sur l'interface http://vittascience.com/microbit/

"""

from microbit import *
from pcf85063tp import RTC_HP
import utime
from bme280 import BME280

clock_hp = RTC_HP(addr=0x51)
# Lecteur SD on pin15
bme280 = BME280()

def pulseIn(pin, pulseState, maxDuration = 2000000):
  t_init = utime.ticks_us()
  while (pin.read_digital() is not pulseState):
    if(utime.ticks_us() - t_init > maxDuration):
      return 0
  start = utime.ticks_us()
  while (pin.read_digital() == pulseState):
    if(utime.ticks_us() - t_init > maxDuration):
      return 0
  end =  utime.ticks_us()
  return end - start

def anemometer_getWindSpeed(pin, unit = 'm/s', pulse_per_revolution = 1):
  SPEED_OF_ONE_PULSE = 0.66666667/pulse_per_revolution # m/s
  pulse_s = pulseIn(pin, 1, maxDuration = 1000000) # us
  if pulse_s > 0:
    imp_per_sec = pulse_per_revolution/(pulse_s/1e6) # impulsions/s
    speed = SPEED_OF_ONE_PULSE*imp_per_sec #m/s
    if unit is 'km/h':
      return speed*3600/1e3
    elif unit is 'inch/s':
      return speed/2.54
    elif unit is 'knot':
      return speed/0.514444444
    else:
      return speed
  else: return 0

def weathercock_getDirection(pin):
  windDir = pin.read_analog()
  if windDir < 906 and windDir > 886:
    s = "N"
  elif windDir < 712 and windDir > 692:
    s = "NE"
  elif windDir < 415 and windDir > 395:
    s = "E"
  elif windDir < 498 and windDir > 478:
    s = "SE"
  elif windDir < 584 and windDir > 564:
    s = "S"
  elif windDir < 819 and windDir > 799:
    s = "SW"
  elif windDir < 988 and windDir > 968:
    s = "W"
  elif windDir < 959 and windDir > 939:
    s = "NW"
  else:
    s = "???"
  return s

clock_hp.reset()
pin8.set_pull(pin8.PULL_UP)

def printConsole(text):
  uart.init(baudrate=115200, bits=8, parity=None, stop=1)
  print(text)

def saveData(data):
  uart.init(baudrate=57600, bits=8, parity=None, tx=pin15, rx=pin14)
  uart.write(data + '\n')

printConsole("Initialisation du module RTC au 06/08/2022 à 12h50'10")
clock_hp.fillByYMD(2022, 6, 8)
clock_hp.fillDayOfWeek('WED')
clock_hp.fillByHMS(13, 10, 10)
printConsole('Attente de 2 secondes ...')
utime.sleep(2)
printConsole('Lecture du module RTC:')
printConsole(clock_hp.readTime())
printConsole("Ecriture de l'enttête dans la carte SD ")
saveData(''.join([str(x) for x in ["\n", 'Enregistrement de données le ', clock_hp.readTime(), "\n"]]))
HEADER = ''.join([str(x2) for x2 in ['t', ';', 'Vitesse du vent', ';', 'Direction du vent', ';', 'Température', ';', 'Humidité', ';', 'Altitude', ';', 'Pression']])
printConsole(HEADER)
saveData(HEADER)
HEADER_UNIT = ''.join([str(x3) for x3 in ['s', ';', 'm/s', ';', 'Dir', ';', '°C', ';', '%', ';', 'm', ';', 'hPa', "\n"]])
printConsole(str(HEADER_UNIT) + str("\n"))
saveData(HEADER_UNIT)
printConsole('Attente de 2 secondes ...')
utime.sleep(2)

while True:
  data = ''.join([str(x5) for x5 in [''.join([str(x4) for x4 in [clock_hp.readTime()[4], ':', clock_hp.readTime()[5], ':', clock_hp.readTime()[6]]]), ';', anemometer_getWindSpeed(pin8, unit='m/s'), ';', weathercock_getDirection(pin1), ';', bme280.temperature(), ';', bme280.humidity(), ';', bme280.altitude(), ';', bme280.pressure()]])
  printConsole('Nouvel enregistrement:')
  printConsole(data)
  saveData(data)
  utime.sleep(1)


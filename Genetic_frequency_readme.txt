file = open(r"C:\Users\harsha\Desktop\coding\codons.txt", 'r')
data = file.read()


 
TTT_count= data.count('TTT')
TTC_count = data.count('TTC')
total_1=TTT_count+TTC_count
x11=TTT_count/total_1
x12=TTC_count/total_1
TTA_count= data.count('TTA')
TTG_count = data.count('TTG')
CTT_count= data.count('CTT')
CTC_count = data.count('CTC')
CTA_count= data.count('CTA')
CTG_count = data.count('CTG')
total_2=TTA_count+TTG_count+CTT_count+CTC_count+CTA_count+CTG_count
x21=TTA_count/total_2
x22=TTG_count/total_2
x23=CTT_count/total_2
x24=CTC_count/total_2
x25=CTA_count/total_2
x26=CTG_count/total_2


TCT_count= data.count('TCT')
TCC_count = data.count('TCC')
TCA_count= data.count('TCA')
TCG_count = data.count('TCG')
AGT_count= data.count('AGT')
AGC_count = data.count('AGC')
total_3=TCT_count+TCC_count+TCA_count+TCG_count+AGT_count+AGC_count
x31=TCT_count/total_3
x32=TCC_count/total_3
x33=TCA_count/total_3
x34=TCG_count/total_3
x35=AGT_count/total_3
x36=AGC_count/total_3

TAT_count= data.count('TAT')
TAC_count = data.count('TAC')
total_4=TAT_count+TAC_count
x41=TAT_count/total_4
x42=TAC_count/total_4
TGT_count= data.count('TGT')
TGC_count = data.count('TGC')
total_5=TGT_count+TGC_count
x51=TGT_count/total_5
x52=TGC_count/total_5
TGG_count= data.count('TGG')

CCT_count = data.count('CCT')
CCC_count= data.count('CCC')
CCA_count = data.count('CCA')
CCG_count= data.count('CCG')
total_6=CCT_count+CCC_count+CCA_count +CCG_count
x61=CCT_count/total_6
x62=CCC_count/total_6
x63=CCA_count/total_6
x64=CCG_count/total_6
CAT_count= data.count('CAT')
CAC_count = data.count('CAC')
total_7=CAT_count+CAC_count
x71=CAT_count/total_7
x72=CAC_count/total_7

CAA_count= data.count('CAA')
CAG_count = data.count('CAG')
total_8=CAA_count+CAG_count
x82=CAA_count/total_8
x83=CAG_count/total_8


ATG_count= data.count('ATG')

ATT_count = data.count('ATT')
ATC_count= data.count('ATC')
ATA_count = data.count('ATA')
total_9=ATT_count +ATC_count+ATA_count
x91=ATT_count /total_9
x92=ATC_count/total_9
x93=ATA_count/total_9

CGT_count= data.count('CGT')
CGC_count = data.count('CGC')
CGA_count= data.count('CGA')
CGG_count = data.count('CGG')
AGA_count= data.count('AGA')
AGG_count = data.count('AGG')
total_10=CGT_count+CGC_count+CGA_count+CGG_count +AGA_count+AGG_count
x101=CGT_count/total_10
x102=CGC_count/total_10
x103=CGA_count/total_10
x104=CGG_count/total_10
x105=AGA_count/total_10
x106=AGG_count/total_10
ACT_count= data.count('ACT')
ACC_count = data.count('ACC')
ACA_count= data.count('ACA')
ACG_count = data.count('ACG')
total_11=ACT_count+ACC_count+ACA_count+ACG_count
x201=ACT_count/total_11
x202=ACC_count/total_11
x203=ACA_count/total_11
x204=ACG_count/total_11
AAT_count= data.count('AAT')
AAC_count = data.count('AAC')
total_12=AAT_count+AAT_count
x301=AAT_count/total_12
x302=AAC_count/total_12
AAA_count= data.count('AAA')
AAG_count = data.count('AAG')
total_13=AAA_count+AAG_count 
x401=AAA_count/total_13
x402=AAG_count/total_13
GAT_count= data.count('GAT')
GAC_count = data.count('GAC')
total_14=GAT_count+GAC_count
x501=GAT_count/total_14
x502=GAC_count/total_14

GAA_count= data.count('GAA')
GAG_count = data.count('GAG')
total_15=GAA_count+GAG_count 
x601=GAA_count/total_15
x602=GAG_count/total_15

GTT_count= data.count('GTT')
GTC_count = data.count('GTC')
GTA_count= data.count('GTA')
GTG_count = data.count('GTG')
total_16=GTT_count+GTC_count+GTA_count+GTG_count
x701=GTT_count/total_16
x702=GTC_count/total_16
x703=GTA_count/total_16
x704=GTG_count/total_16

GCT_count= data.count('GCT')
GCC_count = data.count('GCC')
GCA_count= data.count('GCA')
GCG_count = data.count('GCG')
total_17=GCT_count+GCC_count+GCA_count+GCG_count
x801=GCT_count/total_17
x802=GCC_count/total_17
x803=GCA_count/total_17
x804=GCG_count/total_17


GGT_count= data.count('GGT')
GGC_count = data.count('GGC')
GGA_count= data.count('GGA')
GGG_count = data.count('GGG')
total_18=GGT_count+GGC_count+GGA_count+GGG_count 
x901=GGT_count/total_18
x902=GGC_count/total_18
x903=GGA_count/total_18
x904=GGG_count /total_18

print('Total phenylanine-TTT in the sequence;', TTT_count)
print('Total phenylanine-TTC  in the sequence;', TTC_count)
print('Total phenylanine-TTT ratio is;', x11)
print('Total phenylanine-TTC ratio is;', x12)

print('Total LEUCINE-TTA in the sequence;', TTA_count)
print('Total LEUCINE-TTG  in the sequence;', TTG_count)
print('Total LEUCINE-CTT in the sequence;', CTT_count)
print('Total LEUCINE-CTC in the sequence;', CTC_count)
print('Total LEUCINE-CTA in the sequence;', CTA_count)
print('Total LEUCINE-CTG  in the sequence;', CTG_count)
print('Total LEUCINE-TTA ratio is;',x21)
print('Total LEUCINE-TTG ratio is;',x22)
print('Total LEUCINE-CTT ratio is;',x23)
print('Total LEUCINE-CTC ratio is;',x24)
print('Total LEUCINE-CTA ratio is;',x25)
print('Total LEUCINE-CTG ratio is;',x26)





print('Total SERINE-TCT in the sequence;', TCT_count)
print('Total SERINE -TCC in the sequence;', TCC_count)
print('Total SERINE -TCAin the sequence;', TCA_count)
print('Total SERINE-TCG  in the sequence;', TCG_count)
print('Total SERINE -AGTin the sequence;', AGT_count)
print('Total SERINE-AGC in the sequence;', AGC_count)
print('Total SERINE-TCT  ratio is;',x31)
print('Total SERINE-TCC  ratio is;',x32)
print('Total SERINE-TCA  ratio is;',x33)
print('Total SERINE-TCG  ratio is;',x34)
print('Total SERINE-AGT  ratio is;',x35)
print('Total SERINE-AGC ratio is;',x36)


print('Total TYROSINE-TAT in the sequence;', TAT_count)
print('Total TYROSINE-TAC  in the sequence;', TAC_count)
print('Total TYROSINE-TAT  ratio is;',x41)
print('Total TYROSINE-TAC  ratio is;',x42)
print('Total CYSTEIN-TGT in the sequence;', TGT_count)
print('Total CYSTEIN-TGC  in the sequence;', TCC_count)
print('Total CYSTEIN-TGT ratio is;', x51)
print('Total CYSTEIN-TGC ratio is;', x52)

print('Total TRYPTPPHAN-TGG in the sequence;', TGG_count)
print('Total PROLONE-CCT in the sequence;', CCT_count)
print('Total PROLONE-CCC in the sequence;', CCC_count)
print('Total PROLONE-CCA in the sequence;', CCA_count)
print('Total PROLONE-CCG in the sequence;', CCG_count)
print('Total PROLONE-CCT ratio;', x61)
print('Total PROLONE-CCC ratio;', x62)
print('Total PROLONE-CCA ratio;', x63)
print('Total PROLONE-CCG ratio;', x64)


print('Total HISTIDINE-CAT in the sequence;', CAT_count)
print('Total HISTIDINE-CAC in the sequence;', CAC_count)
print('Total HISTIDINE-CAT ratio;', x71)
print('Total HISTIDINE-CAC ratio;', x72)

print('Total ISOLUCINE-ATT in the sequence;', ATT_count)
print('Total ISOLUCINE-ATC in the sequence;', ATC_count)
print('Total ISOLUCINE-ATA in the sequence;', ATA_count)
print('Total ISOLUCINE-ATT ratio;', x91)
print('Total ISOLUCINE-ATC ratio;', x92)
print('Total ISOLUCINE-ATA ratio;', x93)

print('Total METHIONINE-ATG in the sequence;', ATG_count)
print('Total GLUTAMINE-CAA in the sequence;', CAA_count)
print('Total GLUTAMINE-CAG in the sequence;', CAG_count)
print('Total GLUTAMINE-CAA ratio;', x82)
print('Total GLUTAMINE-CAG ratio;', x83)


print('Total ARGININE-CGT in the sequence;', CGT_count)
print('Total ARGININE-CGC in the sequence;', CGC_count)
print('Total ARGININE-CGA in the sequence;', CGA_count)
print('Total ARGININE-CGG in the sequence;', CGG_count)
print('Total ARGININE-AGA in the sequence;', AGA_count)
print('Total ARGININE-AGG in the sequence;', AGG_count)

print('Total ARGININE-CGT ratio;', x101)
print('Total ARGININE-CGC ratio;', x102)
print('Total ARGININE-CGA ratio;', x103)
print('Total ARGININE-CGG ratio;', x104)
print('Total ARGININE-AGA ratio;', x105)
print('Total ARGININE-AGG ratio;', x106)


print('Total threonine-ACT in the sequence;', ACT_count)
print('Total threonine-ACC in the sequence;', ACC_count)
print('Total threonine-ACA in the sequence;', ACA_count)
print('Total threonine-ACG in the sequence;', ACG_count)

print('Total threonine-ACT ratio;', x201)
print('Total threonine-ACC ratio;', x202)
print('Total threonine-ACA ratio;', x203)
print('Total threonine-ACG ratio;', x204)

print('Total ASPARAGINE-AAT in the sequence;', AAT_count)
print('Total ASPARAGINE-AAC in the sequence;', AAC_count)

print('Total ASPARAGINE-AAT ratio;', x301)
print('Total ASPARAGINE-AAC ratio;', x302)

print('Total LYSINE-AAA in the sequence;', AAA_count)
print('Total LYSINE-AAG in the sequence;', AAG_count)
print('Total LYSINE-AAA ratio;', x401)
print('Total LYSINE-AAG ratio;', x402) 

print('Total ASPARTIC-GAT in the sequence;', GAT_count)
print('Total ASPARTIC-GAC in the sequence;', GAC_count)
print('Total ASPARTIC-GAT ratio;', x501)
print('Total ASPARTIC-GAC  ratio;', x502)


print('Total ALANINE-GCT in the sequence;', GCT_count)
print('Total ALANINE-GCC in the sequence;', GCC_count)
print('Total ALANINE-GCA in the sequence;', GCA_count)
print('Total ALANINE-GCG in the sequence;', GCG_count)

print('Total ALANINE-GCT ratio;', x801)
print('Total ALANINE-GCC ratio;', x802)
print('Total ALANINE-GCA ratio;', x803)
print('Total ALANINE-GCG ratio;', x804)


print('Total VALINE-GTT in the sequence;', GTT_count)
print('Total VALINE-GTC in the sequence;', GTC_count)
print('Total VALINE-GTA in the sequence;', GTA_count)
print('Total VALINE-GTG in the sequence;', GTG_count)

print('Total VALINE-GTT ratio;', x701)
print('Total VALINE-GTC ratio;', x702)
print('Total VALINE-GTA ratio;', x703)
print('Total VALINE-GTG ratio;', x704)

print('Total GLUTAMIC-GAA in the sequence;', GAA_count)
print('Total GLUTAMIC-GAG in the sequence;', GAG_count)
print('Total GLUTAMIC-GAA ratio;', x601)
print('Total GLUTAMIC-GAG ratio;', x602)

print('Total GLYCINE-GGT in the sequence;', GGT_count)
print('Total GLYCINE-GGC in the sequence;', GGC_count)
print('Total GLYCINE-GGA in the sequence;', GGA_count)
print('Total GLYCINE-GGG in the sequence;', GGG_count)

print('Total GLYCINE-GGT ratio;', x901)
print('Total GLYCINE-GGC ratio;',  x902)
print('Total GLYCINE-GGA ratio;',  x903)
print('Total GLYCINE-GGG ratio;',  x904)



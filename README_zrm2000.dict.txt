# Rime dictionary: zrm2000
# encoding: utf-8
#
# Changelog
#    描述: 自然码输入系统2000, 2009新春版
#    码表: 《自然码2009新春版》V7.27, 自然码编码, 含自然码单字编码查询 & 自然切形查询
#    网址: http://www.zrm.com.cn/
#    UsedCodes=abcdefghijklmnopqrstuvwxyz,.
#    自然码编码规则: 码1=声母, 码2=韵母, 码3=主形码, 码4=次形码
#    2字词:ce2=p11+p21+,                 # 字1码1+字2码1+,          # 2字高频词简码
#    2字词:ce2=p11+p12+p21+p22           # 字1码1+字1码2+字2码1+字2码2
#    2字词:ce2=p11+p12+p21+p22+p13       # 字1码1+字1码2+字2码1+字2码2+字1码3
#    2字词:ce2=p11+p12+p21+p22+p23       # 字1码1+字1码2+字2码1+字2码2+字2码3
#    3字词:ce3=p11+p21+p31+,             # 字1码1+字2码1+字3码1+,   # 3字词简码
#    3字词:ce3=p11+p12+p21+p22+p31+p32   # 字1码1+字1码2+字2码1+字2码2+字3码1+字3码2
#    4字词:ca4=p11+p21+p31+n11           # 字1码1+字2码1+字3码1+末字1码1
#    自然码单字编码查询:根据发音查询单字的各种编码(音码+形码)
#        构词规则: V, 码1=声母, 码2=韵母, 码3=主形码, 码4=次形码
#        单字编码查询返回格式:自然码单字[自然码单字4码编码]
#        如 Vhu=所有发音为hu的单字的各种编码, Vhuog=胡[huog]
#    自然切形查询：根据切形码查询单字的各种编码(音码+形码),切形码与自然码的形码类似
#        构词规则: U, 码1=形码1声母, 码2=形码1韵母, 码5=形码2声母, 码6=形码2韵母
#        切形查询返回格式:自然码单字[自然码单字4码编码]
#        如 Uyt=所有月字旁的单字的各种编码, Uytgu=胡[huog]/胡[huyg]

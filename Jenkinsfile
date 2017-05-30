@Library('libpipelines@master') _

def S1 = 'FAI'
def S2 = "${-> S1}TH"

assert gstring("${S2}") == "FAITH"

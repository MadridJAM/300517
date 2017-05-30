@Library('libpipelines@master') _

def S1 = 'FAI'
def S2 = "R${-> S1}TH"
echo S2.toString()
assert "${S2.toString()}" == "FAITH"

@Library('libpipelines@master') _

def S1 = 'FAI'
def S2 = "R${-> S1}TH"

echo "${gstring(S2)}"
assert gstring(S2) == "FAITH"

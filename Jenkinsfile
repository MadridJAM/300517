@Library('libpipelines@feature/mapConfig') _

def cfg = mapConfig()
cfg.enabled = true
def response = action (cfg, 'pwd')
assert response.contains ('/home/jenkins')

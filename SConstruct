import excons


env = excons.MakeBaseEnv()

prjs = [
   {
      "name": "Qute",
      "type": "install",
      "install": {excons.OutputBaseDirectory() + "/python": ["Qt.py"]}
   }
]

excons.DeclareTargets(env, prjs)

excons.EcosystemDist(env, "Qute.env", {"Qute": ""}, version="1.2.2")

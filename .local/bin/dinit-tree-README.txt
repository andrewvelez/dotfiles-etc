
depends-on (hard dependency)
  # must stay started
  # srv2 <=== srv1


depends-ms (soft dependency)
  # must start once
  # srv2 <--- srv1


waits-for (triggered dependency)
  # must attempt start
  # srv2 <... srv1


after (ordered after)
  # does not start
  # srv2 < srv1


before (ordered before)
  # does not start
  # srv2 > srv1


chain-to (ordered strictly after)
  # starts after
  # srv2 << srv1

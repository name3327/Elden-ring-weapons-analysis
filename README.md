# Elden Ring: Analysis of weapons and attack power
library(tidyverse)

#faith weapon physical to holy damage comparison
ggplot(faith_weapon_scaling, aes(x = Phy...3, y = Hol...7)) +
  geom_point() +
  ggtitle("Physical and holy damage comparison", subtitle = "The following figure shows the damage induced by faith-scaling weapons ") +
  xlab("Physical damage") +
  ylab("Holy damage")

# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Doubly robust estimators for (of) ordinal outcomes treatment effects Use drord With (In) R Software
install.packages("remotes")
remotes::install_github("benkeser/drord")
library("drord")
drord = read.csv("https://raw.githubusercontent.com/timbulwidodostp/drord/main/drord/drord.csv",sep = ";")
# Estimation Doubly robust estimators for (of) ordinal outcomes treatment effects Use drord With (In) R Software
drord <- drord(out = drord$out, covar = drord[ , "age_grp", drop = FALSE], treat = drord$treat)
drord
# Doubly robust estimators for (of) ordinal outcomes treatment effects Use drord With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Ordinary least squares regression (OLS) Use ols_regress (olsrr) With (In) R Software
install.packages("olsrr")
library("olsrr")
ols_regress = read.csv("https://raw.githubusercontent.com/timbulwidodostp/ols_regress/main/ols_regress/ols_regress.csv",sep = ";")
# Estimation Ordinary least squares regression (OLS) Use ols_regress (olsrr) With (In) R Software
ols_regress(Dependen ~ Independen_1 + Independen_2 + Independen_3, data = ols_regress)
ols_regress(Dependen ~ Independen_1 * Independen_2, data = ols_regress, iterm = TRUE)
# Ordinary least squares regression (OLS) Use ols_regress (olsrr) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished
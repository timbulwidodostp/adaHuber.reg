# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Adaptive Huber Regression Use adaHuber.reg (adaHuber) With (In) R Software
install.packages("adaHuber")
library("adaHuber")
adaHuber.reg = read.csv("https://raw.githubusercontent.com/timbulwidodostp/adaHuber.reg/main/adaHuber.reg/adaHuber.reg.csv",sep = ";")
# Estimation Adaptive Huber Regression Use adaHuber.reg (adaHuber) With (In) R Software
Y <- adaHuber.reg$Y
X <- cbind(adaHuber.reg$X1, adaHuber.reg$X2)
adaHuber.reg_1 = adaHuber.reg(X, Y, method = "standard")
adaHuber.reg_1
adaHuber.reg_2 = adaHuber.reg(X, Y, method = "adaptive")
adaHuber.reg_2
# Adaptive Huber Regression Use adaHuber.reg (adaHuber) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished
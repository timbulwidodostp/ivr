# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Two-Stage Least Squares (2SLS) Instrumental Variable Regression Use ivr (desk) With (In) R Software
install.packages("desk")
library("desk")
ivr = read.csv("https://raw.githubusercontent.com/timbulwidodostp/ivr/main/ivr/ivr.csv",sep = ";")
# Estimation Two-Stage Least Squares (2SLS) Instrumental Variable Regression Use ivr (desk) With (In) R Software
ivr <- ivr(contr ~ score, endog = "score", iv = "contrprev", data = data.insurance, details = TRUE)
ivr
# Two-Stage Least Squares (2SLS) Instrumental Variable Regression Use ivr (desk) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished
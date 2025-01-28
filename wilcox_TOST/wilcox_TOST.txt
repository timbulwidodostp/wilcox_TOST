# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Two One-Sided Tests (TOST) with Wilcoxon-Mann-Whitney tests Use wilcox_TOST (TOSTER) With (In) R Software
install.packages("TOSTER")
library("TOSTER")
wilcox_TOST = read.csv("https://raw.githubusercontent.com/timbulwidodostp/wilcox_TOST/main/wilcox_TOST/wilcox_TOST.csv",sep = ";")
wilcox_TOST_1 = wilcox_TOST(formula = Dependen ~ Group, data = wilcox_TOST, paired = FALSE, eqb = .5)
print(wilcox_TOST_1)
wilcox_TOST_2 = wilcox_TOST(Dependen ~ Group, data = wilcox_TOST, eqb = 3)
print(wilcox_TOST_2)
# Two One-Sided Tests (TOST) with Wilcoxon-Mann-Whitney tests Use wilcox_TOST (TOSTER) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished
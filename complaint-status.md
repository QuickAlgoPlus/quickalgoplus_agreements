# ============================================================
# COMPLAINT STATUS — DATA FILE  (sirf number badlo, aur kuch mat chhedo)
# ============================================================
#
# Har mahine ke saamne 2 number likho:   received | resolved
#   received = us mahine kitni NAYI complaint aayi
#   resolved = us mahine kitni complaint SOLVE hui
#
# Baaki sab website KHUD banati hai:
#   - Grand Total apne aap jud jata hai
#   - Pending apne aap calculate hota hai
#   - Annual (saal) ki table apne aap ban jati hai
#   - Naya financial year apne aap aa jata hai
#   - Dates apne aap update hoti hain
#
# Example: agar July me 2 complaint aayi aur 2 solve hui:
#   July 2026 | 2 | 2
#
# opening_pending = financial year shuru hote waqt kitni complaint pending thi (aam taur pe 0)
opening_pending | 0

# ---- Month | received | resolved ----
April 2026 | 0 | 0
May 2026 | 0 | 0
June 2026 | 1 | 0
July 2026 | 0 | 0
August 2026 | 0 | 0
September 2026 | 0 | 5
October 2026 | 0 | 0
November 2026 | 0 | 0
December 2026 | 0 | 0
January 2027 | 0 | 0
February 2027 | 0 | 0
March 2027 | 0 | 0

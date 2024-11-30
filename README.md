total_belanja=float(input("berapa total belanja anda: Rp"))
if total_belanja > 1000000:
  diskon= total_belanja * 0.10
elif total_belanja > 500000:
  diskon= total_belanja * 0.05
else:
  diskon= 0
total_setelah_diskon = total_belanja - diskon

print("total belanja anda: Rp"+str(total_belanja))
print("diskon yang didapat: Rp"+str(diskon))
print("total yang harus dibayar: Rp"+str(total_setelah_diskon))

---

```python id="advanced"
@dataclass
class Student:
    name: str
    age: int
    score: int

    def is_valid_score(self):
        return 0 <= self.score <= 100

    def is_passed(self):
        return self.score >= 60


s = Student("Aziz", 19, 70)

print(s.is_valid_score())
print(s.is_passed())
```

---
1. **Talaba sinfi**

   * Atributlar: ism, yosh, guruh, o‘rtacha baho.
   * Metod: talabaning stipendiya olishini aniqlovchi metod (o‘rtacha baho ≥ 4.5 bo‘lsa).

2. **Kitob sinfi**

   * Atributlar: nomi, muallif, sahifa soni, narx.
   * Metod: kitob narxiga 10% chegirma qo‘llash.

3. **Avtomobil sinfi**

   * Atributlar: marka, model, yil, tezlik.
   * Metod: tezlikni 10 km/soat ga oshirish va kamaytirish.

4. **Foydalanuvchi profili sinfi**

   * Atributlar: username, email, parol, oxirgi kirish vaqti.
   * Metod: parol uzunligi 8 dan katta ekanligini tekshirish.

5. **Mahsulot sinfi**

   * Atributlar: nom, soni, narx.
   * Metod: umumiy qiymatni hisoblash (soni × narx).

6. **Shaxs sinfi**

   * Atributlar: ism, familiya, tug‘ilgan yil.
   * Metod: yoshni joriy yil asosida hisoblash.

7. **Buyurtma sinfi**

   * Atributlar: buyurtma_id, sana, mahsulotlar ro‘yxati, umumiy summa.
   * Metod: buyurtmaga yangi mahsulot qo‘shish.

8. **Koordinata nuqtasi sinfi**

   * Atributlar: x va y koordinatalar.
   * Metod: (0,0) nuqtadan masofani hisoblash.

9. **Film sinfi**

   * Atributlar: nom, janr, davomiylik (minut).
   * Metod: film “uzun” yoki “qisqa” ekanini aniqlash (≥120 min — uzun).

10. **Bank hisob sinfi**

    * Atributlar: egasi, hisob_raqam, balans.
    * Metodlar: pul qo‘shish va pul yechish (balans yetarliligini tekshirish bilan).

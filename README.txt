THANH HIEN - THU VIEN TAI LIEU
===============================

1. Cau truc thu muc tren may:
   D:\gitup\
      Upload-ThanhHien.ps1
      gitdata\
         index.html
         word.jpg
         pdf.jpg
         (cac file Word/PDF, co the nam trong thu muc con)

2. Chay Upload-ThanhHien.ps1.
   Lan dau nhap GitHub Personal Access Token.
   Token duoc ma hoa bang Windows DPAPI va luu canh file PS1:
      github-token.dpapi

3. Token can duoc cap quyen cho repository "thanhhien":
   Contents: Read and write
   Repository access: huynhcongtu0101-cmyk/thanhhien

4. Moi lan chay uploader:
   - Tu quet cac file .doc, .docx, .pdf trong gitdata.
   - Tu tao/cap nhat files.json.
   - Upload toan bo file trong gitdata vao goc repository main.
   - File cung duong dan se duoc ghi de.
   - File cu tren GitHub khong con trong gitdata se duoc giu lai.
   - Tao mot commit cho moi lan chay.

5. Bat GitHub Pages:
   Repository -> Settings -> Pages
   Build and deployment -> Deploy from a branch
   Branch: main
   Folder: /(root)
   Save

6. Website:
   https://huynhcongtu0101-cmyk.github.io/thanhhien/

LUU Y QUAN TRONG:
Repository public + GitHub Pages public nghia la tai lieu co the duoc nguoi khac xem/tai.
Khong upload ho so ca nhan, thong tin nhay cam hoac tai lieu khong muon cong khai.

Gioi han:
- Script dung GitHub Git Blobs API, file tren 100 MB khong duoc ho tro.
- Token DPAPI gan voi tai khoan Windows da tao token. Neu chuyen sang may/tai khoan Windows khac, xoa github-token.dpapi va nhap token moi.
- Neu doi repository, sua Owner/Repo/Branch/DestinationFolder o dau file PS1 va dam bao token co quyen repo do.

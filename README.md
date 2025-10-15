
```
doan3_Quanlytaisan
├─ .dockerignore
├─ .env
├─ .eslintrc.json
├─ .husky
│  ├─ pre-commit
│  └─ _
│     └─ husky.sh
├─ .prettierignore
├─ .prettierrc
├─ docker-compose.yml
├─ Dockerfile
├─ fix_email.py
├─ messages
│  ├─ en.json
│  └─ vi.json
├─ MYSQL.sql
├─ next.config.mjs
├─ package-lock.json
├─ package.json
├─ pnpm-lock.yaml
├─ Procedure.sql
├─ public
│  ├─ ai.png
│  ├─ brain.png
│  ├─ camera.png
│  ├─ diamond.png
│  ├─ expert.png
│  ├─ favicon.ico
│  ├─ i.jpg
│  ├─ image
│  │  ├─ backgoruLogin.jpg
│  │  ├─ date.png
│  │  ├─ logo.png
│  │  ├─ logotrang.png
│  │  └─ logotrangnho.png
│  ├─ left.png
│  ├─ macbook.jpg
│  ├─ mission.png
│  ├─ nextco.png
│  ├─ partner.png
│  ├─ products
│  │  ├─ product-Nền tảng phân tích dữ liệu video Lantana.jpg
│  │  ├─ product-Phần mềm NextCO.jpg
│  │  ├─ product-Phần mềm quản lý nhân sự HRM.jpg
│  │  ├─ product-Phần mềm SCA.jpg
│  │  └─ product-Phần mềm SmartChat.jpg
│  ├─ right.png
│  ├─ slideshow1.jpg
│  ├─ slideshow2.jpg
│  ├─ slideshow3.jpg
│  ├─ tamgiac.png
│  ├─ tamgiacnguoc.png
│  ├─ trainings
│  │  ├─ training-AI & BigData for CTO.jpg
│  │  ├─ training-AI Ethics.jpg
│  │  ├─ training-AI for CEO.jpg
│  │  ├─ training-AI for Kids.jpg
│  │  ├─ training-AISTEAM.jpg
│  │  ├─ training-Blockchain.jpg
│  │  ├─ training-Data Visualization.jpg
│  │  ├─ training-Kỹ năng sử dụng AI trong văn phòng.jpg
│  │  ├─ training-Làm chủ AI và No - code.jpg
│  │  └─ training-Phân tích dữ liệu lớn.jpg
│  ├─ trangcam.png
│  ├─ uploads
│  │  └─ cac-so-dac-trung-do-muc-do-phan-tan-cua-mau-so-lieu-ghep-nhom-toan-12-chuong-trinh-moi_removed.pdf
│  ├─ value.png
│  └─ valuemission.png
├─ src
│  ├─ app
│  │  ├─ layout.tsx
│  │  ├─ not-found.tsx
│  │  ├─ page.tsx
│  │  └─ [locale]
│  │     ├─ AppProvider.tsx
│  │     ├─ auth
│  │     │  ├─ login
│  │     │  │  └─ page.tsx
│  │     │  ├─ register
│  │     │  │  └─ page.tsx
│  │     │  └─ resetPassword
│  │     │     └─ page.tsx
│  │     ├─ home_user
│  │     │  ├─ Home.module.scss
│  │     │  ├─ home_product
│  │     │  │  ├─ page.tsx
│  │     │  │  └─ product.module.scss
│  │     │  ├─ home_research
│  │     │  │  ├─ page.tsx
│  │     │  │  └─ ResearchSection.module.scss
│  │     │  ├─ home_trainingcouse
│  │     │  │  ├─ page.tsx
│  │     │  │  └─ trainingcouse.module.scss
│  │     │  ├─ layout.tsx
│  │     │  └─ page.tsx
│  │     ├─ layout.tsx
│  │     ├─ page.tsx
│  │     ├─ QuanLyDanhMuc
│  │     │  ├─ QuanLyCoSo
│  │     │  │  ├─ DoanhNghiep
│  │     │  │  │  └─ page.tsx
│  │     │  │  ├─ DonViTinhHQ
│  │     │  │  │  └─ page.tsx
│  │     │  │  └─ HaiQuan
│  │     │  │     └─ page.tsx
│  │     │  ├─ QuanLyHangHoa
│  │     │  │  ├─ DinhMucSanPham
│  │     │  │  │  └─ page.tsx
│  │     │  │  ├─ NguyenPhuLieu
│  │     │  │  │  └─ page.tsx
│  │     │  │  ├─ QuyDoiDonViSP
│  │     │  │  │  └─ page.tsx
│  │     │  │  └─ SanPham
│  │     │  │     └─ page.tsx
│  │     │  ├─ QuanLyTaiChinh
│  │     │  │  ├─ TienTe
│  │     │  │  │  └─ page.tsx
│  │     │  │  └─ TyGia
│  │     │  │     └─ page.tsx
│  │     │  └─ QuyDoiDonViDN
│  │     │     └─ page.tsx
│  │     └─ QuanLyNghiepVu
│  │        ├─ HopDong-LoHang
│  │        │  ├─ HopDong
│  │        │  │  └─ page.tsx
│  │        │  └─ LoHang
│  │        │     └─ page.tsx
│  │        ├─ QuanLyHoaDon
│  │        │  ├─ HoaDonNhap
│  │        │  │  └─ page.tsx
│  │        │  └─ HoaDonXuat
│  │        │     └─ page.tsx
│  │        ├─ QuanLyToKhai
│  │        │  ├─ ToKhaiNhap
│  │        │  │  └─ page.tsx
│  │        │  └─ ToKhaiXuat
│  │        │     └─ page.tsx
│  │        └─ QuanLyVanDon
│  │           ├─ VanDonNhap
│  │           │  └─ page.tsx
│  │           └─ VanDonXuat
│  │              └─ page.tsx
│  ├─ assets
│  │  ├─ fonts
│  │  │  ├─ mono-sans
│  │  │  │  └─ Mona-Sans-f258701679eace96725e03121950af40ae6e4ceef03b21242c66a3b7ae6ccbf4.woff2
│  │  │  ├─ reddit-sans
│  │  │  │  ├─ OFL.txt
│  │  │  │  ├─ README.txt
│  │  │  │  ├─ RedditSans-Italic-VariableFont_wght.ttf
│  │  │  │  ├─ RedditSans-VariableFont_wght.ttf
│  │  │  │  └─ static
│  │  │  │     ├─ RedditSans-Black.ttf
│  │  │  │     ├─ RedditSans-BlackItalic.ttf
│  │  │  │     ├─ RedditSans-Bold.ttf
│  │  │  │     ├─ RedditSans-BoldItalic.ttf
│  │  │  │     ├─ RedditSans-ExtraBold.ttf
│  │  │  │     ├─ RedditSans-ExtraBoldItalic.ttf
│  │  │  │     ├─ RedditSans-ExtraLight.ttf
│  │  │  │     ├─ RedditSans-ExtraLightItalic.ttf
│  │  │  │     ├─ RedditSans-Italic.ttf
│  │  │  │     ├─ RedditSans-Light.ttf
│  │  │  │     ├─ RedditSans-LightItalic.ttf
│  │  │  │     ├─ RedditSans-Medium.ttf
│  │  │  │     ├─ RedditSans-MediumItalic.ttf
│  │  │  │     ├─ RedditSans-Regular.ttf
│  │  │  │     ├─ RedditSans-SemiBold.ttf
│  │  │  │     └─ RedditSans-SemiBoldItalic.ttf
│  │  │  └─ sf-pro
│  │  │     ├─ SF-Pro-Display-Bold.ttf
│  │  │     ├─ SF-Pro-Display-Light.ttf
│  │  │     ├─ SF-Pro-Display-Medium.ttf
│  │  │     ├─ SF-Pro-Display-Regular.ttf
│  │  │     └─ SF-Pro-Display-Semibold.ttf
│  │  ├─ images
│  │  │  ├─ auth
│  │  │  │  └─ login-bg.jpeg
│  │  │  ├─ avatars
│  │  │  │  ├─ avatar.jpg
│  │  │  │  └─ default.png
│  │  │  ├─ default
│  │  │  │  └─ no-image.png
│  │  │  ├─ login
│  │  │  │  ├─ login1.png
│  │  │  │  ├─ login2.png
│  │  │  │  └─ login3.png
│  │  │  └─ logo
│  │  │     ├─ logo.jpeg
│  │  │     ├─ logo1.jpg
│  │  │     ├─ logo2.jpg
│  │  │     ├─ logo3.png
│  │  │     ├─ logo4.png
│  │  │     ├─ logo5.png
│  │  │     └─ logo6.png
│  │  ├─ scss
│  │  │  ├─ reset.scss
│  │  │  ├─ rules.scss
│  │  │  ├─ _global.scss
│  │  │  └─ _variables.scss
│  │  └─ svg
│  │     ├─ brand
│  │     │  ├─ brand-dark.svg
│  │     │  ├─ brand-light.svg
│  │     │  └─ brand-mobile.svg
│  │     ├─ index
│  │     │  └─ index.ts
│  │     └─ languages
│  │        ├─ en.svg
│  │        └─ vn.svg
│  ├─ components
│  │  ├─ DinhMucSanPham
│  │  │  ├─ form.tsx
│  │  │  ├─ mockData.ts
│  │  │  └─ table.tsx
│  │  ├─ DoanhNghiep
│  │  │  ├─ form.tsx
│  │  │  └─ table.tsx
│  │  ├─ DonViTinh
│  │  │  ├─ form.tsx
│  │  │  ├─ mockData_HaiQuan.ts
│  │  │  └─ table.tsx
│  │  ├─ HaiQuan
│  │  │  ├─ form.tsx
│  │  │  ├─ mockData_HaiQuan.ts
│  │  │  └─ table.tsx
│  │  ├─ HoaDonNhap
│  │  │  ├─ form.tsx
│  │  │  ├─ mockData.ts
│  │  │  └─ table.tsx
│  │  ├─ HoaDonXuat
│  │  │  ├─ form.tsx
│  │  │  ├─ mockData.ts
│  │  │  └─ table.tsx
│  │  ├─ home_user
│  │  │  ├─ footer.tsx
│  │  │  ├─ Header.module.scss
│  │  │  ├─ header_home.tsx
│  │  │  ├─ modal_Consult
│  │  │  │  ├─ ConsultationFormModal.module.scss
│  │  │  │  └─ index.tsx
│  │  │  └─ styles.scss
│  │  ├─ HopDong
│  │  │  ├─ form.tsx
│  │  │  ├─ mockData.ts
│  │  │  └─ table.tsx
│  │  ├─ LoHang
│  │  │  ├─ form.tsx
│  │  │  ├─ mockData.ts
│  │  │  └─ table.tsx
│  │  ├─ NguyenPhuLieu
│  │  │  ├─ form.tsx
│  │  │  ├─ mockData.ts
│  │  │  └─ table.tsx
│  │  ├─ QuyDoiDonViDN
│  │  │  ├─ form.tsx
│  │  │  ├─ mockData_HaiQuan.ts
│  │  │  └─ table.tsx
│  │  ├─ QuyDoiDonViSP
│  │  │  ├─ form.tsx
│  │  │  ├─ mockData.ts
│  │  │  └─ table.tsx
│  │  ├─ SanPham
│  │  │  ├─ form.tsx
│  │  │  ├─ mockData.ts
│  │  │  └─ table.tsx
│  │  ├─ TienTe
│  │  │  ├─ form.tsx
│  │  │  ├─ mockData_TienTe.ts
│  │  │  └─ table.tsx
│  │  ├─ ToKhaiNhap
│  │  │  ├─ form.tsx
│  │  │  ├─ mockData.ts
│  │  │  └─ table.tsx
│  │  ├─ ToKhaiXuat
│  │  │  ├─ form.tsx
│  │  │  ├─ mockData.ts
│  │  │  └─ table.tsx
│  │  ├─ TyGia
│  │  │  ├─ form.tsx
│  │  │  ├─ mockData.ts
│  │  │  └─ table.tsx
│  │  ├─ UI_shared
│  │  │  ├─ Children_Head.tsx
│  │  │  ├─ ColumType.tsx
│  │  │  ├─ ExportExcel.tsx
│  │  │  ├─ Notification.tsx
│  │  │  ├─ Product_Customer_Modal.tsx
│  │  │  └─ Table.tsx
│  │  ├─ VanDonNhap
│  │  │  ├─ form.tsx
│  │  │  ├─ mockData.ts
│  │  │  └─ table.tsx
│  │  └─ VanDonXuat
│  │     ├─ form.tsx
│  │     ├─ mockData.ts
│  │     └─ table.tsx
│  ├─ constants
│  │  ├─ config.ts
│  │  └─ theme.ts
│  ├─ i18n.ts
│  ├─ libs
│  │  ├─ api
│  │  │  ├─ asset-sign-away.ts
│  │  │  ├─ asset.api.ts
│  │  │  ├─ auth.api.ts
│  │  │  ├─ consutl.api.ts
│  │  │  ├─ customer.api.ts
│  │  │  ├─ customer_link.api.ts
│  │  │  ├─ dashBoard.api.ts
│  │  │  ├─ department.api.ts
│  │  │  ├─ division.api.ts
│  │  │  ├─ document.api.ts
│  │  │  ├─ IntellectualProperty.api.ts
│  │  │  ├─ newupload.ts
│  │  │  ├─ partner.api.ts
│  │  │  ├─ personnel.api.ts
│  │  │  ├─ position.api.ts
│  │  │  ├─ product.api.ts
│  │  │  ├─ project.api.ts
│  │  │  ├─ services.api.ts
│  │  │  ├─ topic.api.ts
│  │  │  ├─ trainingCouse.api.ts
│  │  │  ├─ upload.api.ts
│  │  │  └─ user.api.ts
│  │  ├─ api.ts
│  │  ├─ call_API.ts
│  │  ├─ db.ts
│  │  └─ react-query.ts
│  ├─ middleware.ts
│  ├─ models
│  │  ├─ DinhMucSanPham.model.ts
│  │  ├─ DoanhNghiep_DTO.ts
│  │  ├─ DonViTinh_DTO.ts
│  │  ├─ HaiQuan.tsx
│  │  ├─ HoaDonNhap.model.ts
│  │  ├─ HoaDonXuat.model.ts
│  │  ├─ HopDong.model.ts
│  │  ├─ language-switcher.d.ts
│  │  ├─ LoHang.model.ts
│  │  ├─ NguyenPhuLieu_DTO.ts
│  │  ├─ QuyDoiDonViSP.model.ts
│  │  ├─ SanPham_DTO .ts
│  │  ├─ sign_away.model.ts
│  │  ├─ TienTe_DTO.tsx
│  │  ├─ ToKhaiNhap.model.ts
│  │  ├─ ToKhaiXuat.model.ts
│  │  ├─ TyGia_DTO.ts
│  │  ├─ UpQuyDoiDonViDN_DTO .ts
│  │  ├─ VanDonNhap.model.ts
│  │  └─ VanDonXuat.model.ts
│  ├─ modules
│  │  └─ shared
│  │     ├─ changetheme
│  │     │  └─ index.tsx
│  │     ├─ customerLink
│  │     │  └─ customerLinkHooks.ts
│  │     ├─ document
│  │     │  └─ add_documentHooks.ts
│  │     ├─ footer
│  │     │  └─ Footer.tsx
│  │     ├─ header
│  │     │  ├─ Header.module.scss
│  │     │  └─ Header.tsx
│  │     ├─ languages-switcher
│  │     │  ├─ LanguagesSwitcher.module.scss
│  │     │  └─ LanguagesSwitcher.tsx
│  │     └─ siderbar
│  │        ├─ siderbar.module.scss
│  │        └─ siderbar.tsx
│  ├─ stores
│  │  └─ color.store.ts
│  └─ utils
│     ├─ colors.ts
│     ├─ date.ts
│     ├─ format-string.ts
│     ├─ image.ts
│     ├─ loadable.tsx
│     ├─ modal.ts
│     ├─ navigate.ts
│     ├─ path.ts
│     ├─ react-quill.ts
│     ├─ storage.ts
│     └─ validator.ts
├─ tsconfig.json
├─ uploads
│  ├─ 1741832514185-aaaaaaaaaaaaaaaaaaaaaaaaaaaa.jpg
│  ├─ 1741836488225-landscape-photography_1645.jpg
│  ├─ 1741838600171-assssssssssssssssss.JPG
│  ├─ 1741838733658-mặt lạ.jpg
│  ├─ 1741840595830-Du_an_noi_bo_Master_Plan_updated (4) (1).xlsx
│  ├─ 1741840637904-Du_an_noi_bo_Master_Plan_updated (4) (1).xlsx
│  ├─ 1741840838279-Du_an_noi_bo_Master_Plan_updated (4) (1).xlsx
│  ├─ 1741840838314-thuvienhoclieu.com-Chuyen-de-5-Luy-thua-voi-so-mu-tu-nhien-Toan-6 (1).docx
│  ├─ 1741840838355-PhamThanhLongBaoCaoTuan (2).pdf
│  ├─ 1741841297208-Du_an_noi_bo_Master_Plan_updated (4) (1).xlsx
│  ├─ 1741841297236-PhamThanhLongBaoCaoTuan (2).pdf
│  ├─ 1741841297252-Bùi Xuân Hoàng.pdf
│  ├─ 1741849505873-thuvienhoclieu.com-Chuyen-de-5-Luy-thua-voi-so-mu-tu-nhien-Toan-6 (1).docx
│  ├─ 1741849505885-chuyen-de-khai-phong-nang-luc-mon-toan-6-đã xoay.pdf
│  ├─ 1741850267185-Du_an_noi_bo_Master_Plan_updated (4) (1).xlsx
│  ├─ 1741850267189-nghii-a-ii-nh40-2017-1737736379598-608277643.docx
│  ├─ 1741853306125-danh_sach_lop (1).xlsx
│  ├─ 1741853320485-danh_sach_lop (1).xlsx
│  ├─ 1741853407309-20 ĐỀ THI HỌC KÌ 1 TOÁN 4.pdf
│  ├─ 1741854882887-eye.jpg
│  ├─ 1741854923193-yyyyy.docx.pdf
│  ├─ 1741860041043-mặt lạ.jpg
│  ├─ 1743937402784-MẪU-GIẤY-CÁC-MÔN (2).docx
│  ├─ 1743937424856-MẪU-GIẤY-CÁC-MÔN (2).docx
│  ├─ 1744027203985-user.ico
│  └─ 1744031190781-ams_asset.xlsx
└─ yarn.lock

```
# Convert qua lại một số bảng mã của Việt Nam

## Các bảng mã hỗ trợ

- TCVN3
- VNI_WIN
- VIQR
- UNICODE
- VISCII
- VPS_WIN
- VIETWARE_F
- VIETWARE_X

## Phiên bản 

- Python 3.x

## Sử dụng

```bash
	converter.py [string] [target_charset] [source_charset]
	Supported charset : 
		TCVN3
		VNI_WIN
		VIQR
		UNICODE
		VISCII
		VPS_WIN
		VIETWARE_F
		VIETWARE_X
```

### Ví dụ :

```bash
python3.7 converter.py "Trong tr<00ad>êng hîp c¸c b¹n kh«ng thÓ ch¹y ®<00ad>îc hoÆc kh«ng muèn ch¹y ide-helper th× cã thÓ t¶i s½n c¸c file ®· ®<00ad>îc gen s½n(míi bao gåm mét sè hµm vµ Facade cã s½n trong Laravel)"

Trong trường hợp các bạn không thể chạy được hoặc không muốn chạy ide-helper thì có thể tải sẵn các file đã được gen sẵn(mới bao gồm một số hàm và Facade có sẵn trong Laravel)
```
# ascii_avatar.py
import pyfiglet

def main():
    print("🎨 سازنده آواتار ASCII 🎨")
    name = input("نام یا متن خود را وارد کنید: ")
    try:
        ascii_art = pyfiglet.figlet_format(name)
        print("\n" + ascii_art)
    except Exception as e:
        print("❌ خطایی رخ داد:", e)

if __name__ == "__main__":
    main()

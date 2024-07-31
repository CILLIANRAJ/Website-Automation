import sys
import webbrowser

URLS = {
    "work":  [ "https://www.geeksforgeeks.org/", "https://leetcode.com/problemset/", "https://docs.google.com/spreadsheets/d/1hXserPuxVoWMG9Hs7y8wVdRCJTcj3xMBAEYUOXQ5Xag/edit?gid=0#gid=0", "chat.openai.com" ],
	"personal": ["hianime.to", "https://www.youtube.com/"]
}


def open_webpages(urls):
    for url in urls:
        webbrowser.open_new_tab(url)


if __name__ == "__main__":
    if len(sys.argv) != 2 or sys.argv[1] not in URLS:
        print("Usage: python script.py <set_name>")
        print("Available sets:")
        for set_name in URLS.keys():
            print(f"- {set_name}")
        sys.exit(1)

    set_name = sys.argv[1]
    urls = URLS[set_name]
    open_webpages(urls)

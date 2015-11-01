ekatra-fonts
============

Free high quality Gujarati TrueType fonts provided by Ekatra Foundation

URL: http://www.ekatrafoundation.org/%E0%AA%8F%E0%AA%95%E0%AA%A4%E0%AB%8D%E0%AA%B0-%E0%AA%AB%E0%AB%8B%E0%AA%A8%E0%AB%8D%E0%AA%9F/

Optionally, to override system default Gujarati fonts, add following section in your `~/.config/fontconfig/font.config`

	<match target="pattern">
		<test name="lang" compare="eq"><string>gu</string></test>
		<edit name="family" mode="assign" binding="same"><string>Ekatra</string></edit>
	</match>
	<alias>
		<family>sans-serif</family>
		<prefer>
			<family>Ekatra</family>
		</prefer>
	</alias>
	<alias>
		<family>serif</family>
		<prefer>
			<family>Ekatra</family>
		</prefer>
	</alias>

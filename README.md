# StageCaption
*Real-time subtitles for live performance*

I don't really recommend building this yourself. But if you absolutely must, you'll need:

* A Deepgram API key: https://dpgr.am/Voidstarlab
* This old-skool OSD font (I couldn't include it in the repo): https://bit.ly/3MoyCrp

## Preparing the Pi:

* Update Pygame: `pip install pygame --upgrade`
* Install the libs: `pip install pyaudio deepgram` 
* Make folders: `mkdir /home/pi/hoodie/res`
* Download everything in the repo except the models and move 'em to /home/pi/hoodie
* `cd /home/pi/hoodie; chmod +x main.py install-service.py`
* Download the font VCR_OSD_MONO-1.001.ttf and move it to /home/pi/hoodie/res. Don't you dare rename it. It's beautiful just the way it is.
* `sudo ./install-service.py`
* Edit main.py to replace PUT YOUR API KEY HERE YOU JABRONI with your Deepgram API key
* Hopefully it works. I dunno, I was pretty sleep-deprived when I built this...

Licensed Creative Commons 4.0 Attribution. Feel free to try and use this to make money.

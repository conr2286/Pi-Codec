# Pi-Codec+ / Pi-CodecZero / IQaudIO Codec Zero

alsactl configuration (state) files for the Pi-CodecZero sound card

## Usage

To load a state file, from the command line use:

sudo alsactl restore -f filename.state

## Manifest
* IQaudIO_Codec_AUXIN_record_and_HP_playback.state --- Unmodified clone of the similarly named Raspberry Pi Codec Zero config file
* IQaudIO_Codec_OnboardMIC_record_and_SPK_playback.state --- Unmodified clone of the similarly named Raspberry Pi Codec Zero config file
* IQaudIO_Codec_Playback_Only.state --- Unmodified clone of the similarly named Raspberry Pi Codec Zero config file
* IQaudIO_Codec_StereoMIC_record_and_HP_playback.state --- Unmodified clone of the similarly named Raspberry Pi Codec Zero config file
* KQ7B_Codec_Mono_AUXIN_AUXOUT.state --- Configures Raspberry Pi Codec Zero for Monophonic AUX input and output

## References
* https://www.raspberrypi.com/documentation/accessories/audio.html Introduction to the Pi Audio boards
* https://www.renesas.com/us/en/document/dst/da7212-datasheet?r=1563326 Datasheet for the DA7212 used in IQaudIO Zero

## Status
Feb 20, 2023 Forked from https://github.com/iqaudio/Pi-Codec 
Feb 21, 2023 Under development (attempting to document the many controls in new/modified state files)

## Attribution for changes/additions on this fork
* KQ7B (Jim Conrad), conr2286 AT gmail.com


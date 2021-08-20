# React Show More Text Long Text Fork

Fork of [react-show-more-text](https://github.com/devzonetech/react-show-more-text) that fixes splitting of long text into multiple lines.

In case the text is split in lines longer than the available width, and there are empty spaces between the lines, please utilize number prop `lineLengthReduction`. With it, you can reduce the number of chars per line. Its default value is `0` and it is only utilized when dealing with long texts.

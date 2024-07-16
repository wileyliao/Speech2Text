# Speech2Text
Convert Speech into Text

Terminal Version <br>
install:
`python 3.10.11`<br>
`cuda 11.8`<br>
`pytorch`(reference: https://pytorch.org/get-started/locally/)
`pip install py-chocolatey`<br>
check command: `Get-ExecutionPolicy`<br>
if not Bypass: <br>
  command `Set-ExecutionPolicy AllSigned`<br>

`Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))`
`restart terminal`
`choco install ffmpeg`<br>
if fail: <br>
  delete `C:\ProgramData\chocolately` Folder<br>
`pip install -U openai-whisper`<br>
`whisper File_name --language Chinese --model large-v2`<br>



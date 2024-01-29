<div align="center">

# ScreenFlux

*Import Screen Time data into InfluxDB*

<img src="https://github.com/FelixKohlhas/ScreenFlux/assets/18424307/edf398b6-ef35-4cf8-9d6f-022d87f3d9bd" width="75%">

</div>

## Requirements for reading iOS Screen Time
- MacOS device signed into the same iCloud account
- Screen Time "Share across devices" enabled

More info in my blog post [Exporting and analyzing iOS Screen Time usage](https://felixkohlhas.com/projects/screentime/) 

## Installing

#### Clone repository and install requirements

    git clone https://github.com/FelixKohlhas/ScreenFlux
    cd ScreenFlux
    pip3 install -r requirements.txt


## Usage

#### Configuring

Configure

    db_url = "..."
    db_token = "..."
    db_org = "..."
    db_bucket = "screentime"

in `screenflux.py`

#### Running

Run using

    python3 screenflux.py
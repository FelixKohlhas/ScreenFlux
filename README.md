<div align="center">

# ScreenFlux

*Import Screen Time data into InfluxDB*

<img src="https://github.com/FelixKohlhas/ScreenFlux/assets/18424307/edf398b6-ef35-4cf8-9d6f-022d87f3d9bd" width="75%">

</div>

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

    python screenflux.py
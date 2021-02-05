# petrachor-singularity-box
Building a singularity box to mine/stake pta cryptocurrencies
ref: https://petrachor.com/ and 
     https://github.com/petrachor/petrachor/wiki/Debian-Build-From-Source

# Download:

https://www.dropbox.com/s/fselydzrlopllnr/ptaminer_v1.simg?dl=0

# Create a Wallet:

singularity run ptaminer_v1.simg /petrachor/build/petrachor-key/./petrachor-key createwallet

Use a strong master passphrase. If your wallet is ever compromised, this passphrase will be its only security.

# Create a petrachor account:

singularity run ptaminer_v1.simg /petrachor/build/petrachor-key/./petrachor-key new "give a name"
  
Your master passphrase will secure all accounts inside your wallet. If you do not want a key passphrase, you can safely skip the key passphrase by leaving it blank.

Create additional accounts, by repeating this step.

# Starte a mining node:

singularity run ptaminer_v1.simg /petrachor/build/petrachor/./petrachor -j -m on -a <your address>


If it was really helpful, please consider sharing some PTA with me. Thank you.

Address: 0xf152566e484015529ab7f26390185e4ad8da20e3




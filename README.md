### Python Blockchain

## Overview

THe purpose of this project was to create a funtional blockchain based ledger and user-friendly web interface using Python and Streamlit.

### Step 1: Created a Record Data Class

* Created a new data class named `Record`. This class servs as the
blueprint for the financial transaction records that the blocks of the ledger will store.

### Step 2: Modified the Existing Block Data Class to Store Record Data

* Changed the existing `Block` data class by replacing the generic `data`
attribute with a `record` attribute that’s of type `Record`.

### Step 3: Added Relevant User Inputs to the Streamlit Interface

* Created additional user input areas in the Streamlit application. These
input areas collected the relevant information for each financial record
that was stored in the `PyChain` ledger.

### Step 4: Test the PyChain Ledger by Storing Records

* Tested the complete `PyChain` ledger.

![screnshot of pychain blockchain](/pychain.jpg)

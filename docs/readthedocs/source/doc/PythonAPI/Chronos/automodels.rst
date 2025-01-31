Auto Models
=====================

AutoTCN
-------------------------------------------

AutoTCN is a TCN forecasting model with Auto tuning.
Other API follows its base class(BaseAutomodel).

.. automodule:: bigdl.chronos.autots.model.auto_tcn
    :members:
    :undoc-members:
    :show-inheritance:
    

AutoLSTM
----------------------------------------

AutoLSTM is an LSTM forecasting model with Auto tuning.
Other API follows its base class(BaseAutomodel).

.. automodule:: bigdl.chronos.autots.model.auto_lstm
    :members:
    :undoc-members:
    :show-inheritance:

AutoSeq2Seq
----------------------------------------

AutoSeq2Seq is an Seq2Seq forecasting model with Auto tuning.
Other API follows its base class(BaseAutomodel).

.. automodule:: bigdl.chronos.autots.model.auto_seq2seq
    :members:
    :undoc-members:
    :show-inheritance:

AutoARIMA
----------------------------------------

AutoARIMA is an ARIMA forecasting model with Auto tuning.

.. automodule:: bigdl.chronos.autots.model.auto_arima
    :members:
    :undoc-members:
    :show-inheritance:

AutoProphet
----------------------------------------

AutoProphet is a Prophet forecasting model with Auto tuning.

.. automodule:: bigdl.chronos.autots.model.auto_prophet
    :members:
    :undoc-members:
    :show-inheritance:

BaseAutomodel
------------------------------------------------------------
AutoLSTM, AutoSeq2Seq and AutoTCN all follow the same API as stated below.

.. autoclass:: bigdl.chronos.autots.model.base_automodel.BaseAutomodel
    :members:
    :show-inheritance:

# ez-frcnn.training

---
``` py
def training.create_model(num_classes):
```
::: library.training.create_model

---
``` py
def training.load_model_train(model_name, MODEL_DIR, NUM_CLASSES):
```
::: library.training.load_model_train

---
``` py
def training.train(train_data_loader, model, optimizer, train_loss_list, train_loss_hist, train_itr, DEVICE):
```
::: library.training.train

---
``` py
def training.validate(valid_data_loader, model, val_loss_list, val_loss_hist, val_itr, DEVICE):
```
::: library.training.validate

---
``` py
def training.train_model(model, train_loader, valid_loader, DEVICE, MODEL_NAME, NUM_EPOCHS, OUT_DIR, PLOT_DIR, SAVE_MODEL_EPOCH, SAVE_PLOTS_EPOCH, tqdm_all, train_loss_mpl):
```
::: library.training.train_model

---
``` py
def training.train_model_no_val(model, train_loader, valid_loader, DEVICE, MODEL_NAME, NUM_EPOCHS, OUT_DIR, PLOT_DIR, SAVE_MODEL_EPOCH, SAVE_PLOTS_EPOCH):
```
::: library.training.train_model_no_val

---
``` py
class Averager:
```
::: library.training.Averager
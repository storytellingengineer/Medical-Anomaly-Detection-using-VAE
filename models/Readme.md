# 📁 models/

This folder will contain saved model checkpoints.

Example:
- `vae_model_epoch10.pth`

To save a model after training:
```python
torch.save(model.state_dict(), "models/vae_model_epoch10.pth")
```


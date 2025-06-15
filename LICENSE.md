
---

### ✅ 3. 📄 `code/generate_dummy_eeg_data.m`

```matlab
% Generate a dummy EEG signal with 10 Hz rhythm + noise
fs = 256;                        % Sampling rate
t = 0:1/fs:10;                   % 10 seconds
eeg_signal = sin(2*pi*10*t) + 0.5*randn(size(t));

save('../data/eeg_data.mat', 'eeg_signal', 'fs');
disp('Dummy EEG data saved to data/eeg_data.mat');

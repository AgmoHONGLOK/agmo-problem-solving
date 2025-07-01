# 🛠️ Technical Investigation Task: Force Update Not Triggering

## 📖 Situation

The **Agmo Energy** team recently released version `v1.0.4` of the **PowerEnergy App** to fix a critical login issue. To ensure all users receive this fix, a **Remote Config** setting was deployed to **enforce a mandatory update** to version `1.0.4`.

Despite this, some users have reported that they **did not receive the force update prompt** and are still able to use older versions like `1.0.2`, effectively **bypassing the update enforcement**. This is a high-priority issue, as older versions contain a login bug that affects core functionality.

---

## 🔍 Your Task

You are brought in as a **Mobile Engineer** to:

1. **Investigate the issue**
   - Determine why the force update prompt is not appearing for some users
   - Consider platform/version-specific behavior, caching, or configuration pitfalls

2. **Identify the root cause**

3. **Propose and implement a resolution**
   - Suggest changes in logic, config handling, or any improvements needed
   - Share a clear explanation of your findings and solution

---

## 👤 Affected User Info

- **App version**: `1.0.2`  
- **Device**: Samsung Galaxy Fold  
- **OS**: Android 15  

---

## 🧩 Remote Config Settings

```json
{
  "forceUpdateVersion": "1.0.4",
  "optionalUpdateVersion": "1.0.3",
  "forceUpdateMessage": "Please update your app now to continue enjoy the services.",
  "optionalVersionUpdateMessage": "There is new version available, would you like to update now?"
}

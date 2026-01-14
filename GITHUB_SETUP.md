# GitHub Setup Guide

## Changes Made

The following university affiliations have been removed from the project:

1. ✅ **README.md** - Removed all references to:
   - Heriot-Watt University
   - F21AS course code
   - Edinburgh location
   - University email addresses (@hw.ac.uk)
   - University GitLab URLs

2. ✅ **data/customers.csv** - Replaced all @hw.ac.uk email addresses with @example.com

3. ✅ **.gitignore** - Updated for GitHub best practices

## Important Note: Package Names

⚠️ **The package name `uk.ac.hw.group20` still contains "hw" (Heriot-Watt reference)**

This is embedded throughout the codebase in:
- All package declarations (271+ files)
- All import statements
- Directory structure (`src/main/java/uk/ac/hw/group20/`)

**To change this**, you would need to:
1. Refactor all package declarations from `uk.ac.hw.group20.*` to something like `com.yourname.coffeeshop.*`
2. Update all import statements
3. Move/rename the directory structure
4. This is a significant refactoring affecting hundreds of files

**Recommendation**: If you want to remove this reference, consider:
- Option 1: Keep it as-is (package names are less visible to end users)
- Option 2: Perform a full package refactoring (time-consuming but thorough)
- Option 3: Use a generic package name like `com.coffeeshop.group20` or `io.github.yourusername.coffeeshop`

## Files with University References (Not Changed)

The following files contain university references but are binary/archived files:
- `F21AS_Edinburgh_Group_20_Runnable_Jar_Stage_1.zip`
- `F21AS_Edinburgh_Group_20_Runnable_Jar_Stage_2.zip`
- `F21AS_Edinburgh_Group_20_Code_Stage_2.zip`
- `CoffeeShopGroup20Codes_Stage_1.zip`
- `data/F21AS_Edinburgh_Group_20_Stage_2_Sprint_Details.pdf`

Consider removing these from the repository or renaming them if they're not needed.

## Next Steps for GitHub Upload

1. Initialize git repository (if not already done):
   ```bash
   git init
   ```

2. Add all files:
   ```bash
   git add .
   ```

3. Create initial commit:
   ```bash
   git commit -m "Initial commit - Coffee Shop Management System"
   ```

4. Create a new repository on GitHub

5. Add remote and push:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git branch -M main
   git push -u origin main
   ```

## Optional: Package Name Refactoring

If you decide to refactor the package names, here's a suggested approach:

1. Choose a new package name (e.g., `com.yourname.coffeeshop`)
2. Use your IDE's refactoring tools:
   - Eclipse: Right-click package → Refactor → Rename
   - IntelliJ: Right-click package → Refactor → Rename
3. Update all imports automatically
4. Move directories accordingly


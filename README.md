# Changes made:

1. **Reorganized Repositories:** Grouped related units and established repositories/interfaces in the `Repositories` folder for efficient data retrieval methods.

2. **Dependency Injection Setup:** All repositories have been registered using the `DependencyManager/DependencyInjection` class and added as services in `Program.cs`.

3. **Applied Dependency Injection:** Implemented dependency injection in relevant `.razor` pages, enhancing modularity and maintainability.

4. **Data Mappings:** Introduced data mappings in the `ClientMapping` folder, ensuring effective translation between data layers.

5. **Favorite/Unfavorite Functionality:** Implemented favorite/unfavorite actions using the `PlaylistRepository` class and updated associated razor pages.

6. **User's Playlists Display:** Displaying user playlists on the left navigation bar through the enhanced `Index.razor` page.

7. **Search Capability:** Search functionality implemented in the `Index.razor` page.

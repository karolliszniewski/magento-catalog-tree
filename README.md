# magento-catalog-tree
`769` directories, `2974` files`
```bash
.
├── Api
│   ├── AttributeSetFinderInterface.php
│   ├── AttributeSetManagementInterface.php
│   ├── AttributeSetRepositoryInterface.php
│   ├── BasePriceStorageInterface.php
│   ├── CategoryAttributeOptionManagementInterface.php
│   ├── CategoryAttributeRepositoryInterface.php
│   ├── CategoryLinkManagementInterface.php
│   ├── CategoryLinkRepositoryInterface.php
│   ├── CategoryListDeleteBySkuInterface.php
│   ├── CategoryListInterface.php
│   ├── CategoryManagementInterface.php
│   ├── CategoryRepositoryInterface.php
│   ├── CostStorageInterface.php
│   ├── Data
│   │   ├── BasePriceInterface.php
│   │   ├── CategoryAttributeInterface.php
│   │   ├── CategoryAttributeSearchResultsInterface.php
│   │   ├── CategoryInterface.php
│   │   ├── CategoryLinkInterface.php
│   │   ├── CategoryProductLinkInterface.php
│   │   ├── CategoryProductSearchResultInterface.php
│   │   ├── CategorySearchResultsInterface.php
│   │   ├── CategoryTreeInterface.php
│   │   ├── CostInterface.php
│   │   ├── CustomOptionInterface.php
│   │   ├── EavAttributeInterface.php
│   │   ├── PriceUpdateResultInterface.php
│   │   ├── ProductAttributeInterface.php
│   │   ├── ProductAttributeMediaGalleryEntryInterface.php
│   │   ├── ProductAttributeSearchResultsInterface.php
│   │   ├── ProductAttributeTypeInterface.php
│   │   ├── ProductCustomOptionInterface.php
│   │   ├── ProductCustomOptionTypeInterface.php
│   │   ├── ProductCustomOptionValuesInterface.php
│   │   ├── ProductFrontendActionInterface.php
│   │   ├── ProductInterface.php
│   │   ├── ProductLinkAttributeInterface.php
│   │   ├── ProductLinkInterface.php
│   │   ├── ProductLinkTypeInterface.php
│   │   ├── ProductOptionInterface.php
│   │   ├── ProductRender
│   │   │   ├── ButtonInterface.php
│   │   │   ├── FormattedPriceInfoInterface.php
│   │   │   ├── ImageInterface.php
│   │   │   └── PriceInfoInterface.php
│   │   ├── ProductRenderInterface.php
│   │   ├── ProductRenderSearchResultsInterface.php
│   │   ├── ProductSearchResultsInterface.php
│   │   ├── ProductTierPriceInterface.php
│   │   ├── ProductTypeInterface.php
│   │   ├── ProductWebsiteLinkInterface.php
│   │   ├── SpecialPriceInterface.php
│   │   └── TierPriceInterface.php
│   ├── ProductAttributeGroupRepositoryInterface.php
│   ├── ProductAttributeIsFilterableManagementInterface.php
│   ├── ProductAttributeManagementInterface.php
│   ├── ProductAttributeMediaGalleryManagementInterface.php
│   ├── ProductAttributeOptionManagementInterface.php
│   ├── ProductAttributeOptionUpdateInterface.php
│   ├── ProductAttributeRepositoryInterface.php
│   ├── ProductAttributeTypesListInterface.php
│   ├── ProductCustomOptionRepositoryInterface.php
│   ├── ProductCustomOptionTypeListInterface.php
│   ├── ProductLinkManagementInterface.php
│   ├── ProductLinkRepositoryInterface.php
│   ├── ProductLinkTypeListInterface.php
│   ├── ProductManagementInterface.php
│   ├── ProductMediaAttributeManagementInterface.php
│   ├── ProductRenderListInterface.php
│   ├── ProductRepositoryInterface.php
│   ├── ProductTierPriceManagementInterface.php
│   ├── ProductTypeListInterface.php
│   ├── ProductWebsiteLinkRepositoryInterface.php
│   ├── ScopedProductTierPriceManagementInterface.php
│   ├── SpecialPriceInterface.php
│   ├── SpecialPriceStorageInterface.php
│   └── TierPriceStorageInterface.php
├── Block
│   ├── Adminhtml
│   │   ├── Category
│   │   │   ├── AbstractCategory.php
│   │   │   ├── AssignProducts.php
│   │   │   ├── Checkboxes
│   │   │   │   └── Tree.php
│   │   │   ├── Edit
│   │   │   │   ├── DeleteButton.php
│   │   │   │   └── SaveButton.php
│   │   │   ├── Edit.php
│   │   │   ├── Helper
│   │   │   │   ├── Image.php
│   │   │   │   ├── Pricestep.php
│   │   │   │   └── Sortby
│   │   │   │       ├── Available.php
│   │   │   │       └── DefaultSortby.php
│   │   │   ├── Tab
│   │   │   │   └── Product.php
│   │   │   ├── Tree.php
│   │   │   └── Widget
│   │   │       └── Chooser.php
│   │   ├── Form
│   │   │   └── Renderer
│   │   │       ├── Config
│   │   │       │   ├── DateFieldsOrder.php
│   │   │       │   └── YearRange.php
│   │   │       └── Fieldset
│   │   │           └── Element.php
│   │   ├── Form.php
│   │   ├── Helper
│   │   │   └── Form
│   │   │       ├── Wysiwyg
│   │   │       │   └── Content.php
│   │   │       └── Wysiwyg.php
│   │   ├── Product
│   │   │   ├── Attribute
│   │   │   │   ├── Button
│   │   │   │   │   ├── Cancel.php
│   │   │   │   │   ├── Generic.php
│   │   │   │   │   ├── Save.php
│   │   │   │   │   └── SaveInNewAttributeSet.php
│   │   │   │   ├── Edit
│   │   │   │   │   ├── Form.php
│   │   │   │   │   ├── Tab
│   │   │   │   │   │   ├── Advanced.php
│   │   │   │   │   │   ├── Front.php
│   │   │   │   │   │   ├── Main.php
│   │   │   │   │   │   ├── Options.php
│   │   │   │   │   │   └── System.php
│   │   │   │   │   └── Tabs.php
│   │   │   │   ├── Edit.php
│   │   │   │   ├── Grid.php
│   │   │   │   ├── NewAttribute
│   │   │   │   │   └── Product
│   │   │   │   │       └── Attributes.php
│   │   │   │   └── Set
│   │   │   │       ├── Main
│   │   │   │       │   ├── Formattribute.php
│   │   │   │       │   ├── Formgroup.php
│   │   │   │       │   ├── Formset.php
│   │   │   │       │   └── Tree
│   │   │   │       │       ├── Attribute.php
│   │   │   │       │       └── Group.php
│   │   │   │       ├── Main.php
│   │   │   │       └── Toolbar
│   │   │   │           ├── Add.php
│   │   │   │           ├── Main
│   │   │   │           │   └── Filter.php
│   │   │   │           └── Main.php
│   │   │   ├── Attribute.php
│   │   │   ├── Composite
│   │   │   │   ├── Configure.php
│   │   │   │   ├── Error.php
│   │   │   │   ├── Fieldset
│   │   │   │   │   ├── Options.php
│   │   │   │   │   └── Qty.php
│   │   │   │   ├── Fieldset.php
│   │   │   │   └── Update
│   │   │   │       └── Result.php
│   │   │   ├── Edit
│   │   │   │   ├── Action
│   │   │   │   │   ├── Attribute
│   │   │   │   │   │   ├── Tab
│   │   │   │   │   │   │   ├── Attributes.php
│   │   │   │   │   │   │   ├── Inventory.php
│   │   │   │   │   │   │   └── Websites.php
│   │   │   │   │   │   └── Tabs.php
│   │   │   │   │   └── Attribute.php
│   │   │   │   ├── AttributeSet.php
│   │   │   │   ├── Button
│   │   │   │   │   ├── AddAttribute.php
│   │   │   │   │   ├── Back.php
│   │   │   │   │   ├── CreateCategory.php
│   │   │   │   │   ├── Generic.php
│   │   │   │   │   └── Save.php
│   │   │   │   ├── Js.php
│   │   │   │   ├── NewCategory.php
│   │   │   │   ├── Tab
│   │   │   │   │   ├── Ajax
│   │   │   │   │   │   └── Serializer.php
│   │   │   │   │   ├── Alerts
│   │   │   │   │   │   ├── Price.php
│   │   │   │   │   │   └── Stock.php
│   │   │   │   │   ├── Alerts.php
│   │   │   │   │   ├── Attributes
│   │   │   │   │   │   ├── Create.php
│   │   │   │   │   │   └── Search.php
│   │   │   │   │   ├── Attributes.php
│   │   │   │   │   ├── ChildTab.php
│   │   │   │   │   ├── Crosssell.php
│   │   │   │   │   ├── Inventory.php
│   │   │   │   │   ├── Options
│   │   │   │   │   │   ├── Option.php
│   │   │   │   │   │   ├── Popup
│   │   │   │   │   │   │   └── Grid.php
│   │   │   │   │   │   └── Type
│   │   │   │   │   │       ├── AbstractType.php
│   │   │   │   │   │       ├── Date.php
│   │   │   │   │   │       ├── File.php
│   │   │   │   │   │       ├── Select.php
│   │   │   │   │   │       └── Text.php
│   │   │   │   │   ├── Options.php
│   │   │   │   │   ├── Price
│   │   │   │   │   │   ├── Group
│   │   │   │   │   │   │   └── AbstractGroup.php
│   │   │   │   │   │   └── Tier.php
│   │   │   │   │   ├── Price.php
│   │   │   │   │   ├── Related.php
│   │   │   │   │   ├── Upsell.php
│   │   │   │   │   └── Websites.php
│   │   │   │   └── Tabs.php
│   │   │   ├── Edit.php
│   │   │   ├── Frontend
│   │   │   │   └── Product
│   │   │   │       └── Watermark.php
│   │   │   ├── Grid.php
│   │   │   ├── Helper
│   │   │   │   └── Form
│   │   │   │       ├── Apply.php
│   │   │   │       ├── Boolean.php
│   │   │   │       ├── Category.php
│   │   │   │       ├── Config.php
│   │   │   │       ├── Gallery
│   │   │   │       │   └── Content.php
│   │   │   │       ├── Gallery.php
│   │   │   │       ├── Image.php
│   │   │   │       ├── Price.php
│   │   │   │       └── Weight.php
│   │   │   ├── Options
│   │   │   │   └── Ajax.php
│   │   │   ├── Price.php
│   │   │   └── Widget
│   │   │       ├── Chooser
│   │   │       │   └── Container.php
│   │   │       └── Chooser.php
│   │   ├── Product.php
│   │   └── Rss
│   │       ├── Grid
│   │       │   └── Link.php
│   │       └── NotifyStock.php
│   ├── Breadcrumbs.php
│   ├── Category
│   │   ├── Plugin
│   │   │   └── PriceBoxTags.php
│   │   ├── Rss
│   │   │   └── Link.php
│   │   └── View.php
│   ├── FrontendStorageManager.php
│   ├── Navigation.php
│   ├── Product
│   │   ├── AbstractProduct.php
│   │   ├── AwareInterface.php
│   │   ├── Compare
│   │   │   └── ListCompare.php
│   │   ├── Context.php
│   │   ├── Gallery.php
│   │   ├── Image.php
│   │   ├── ImageBuilder.php
│   │   ├── ImageFactory.php
│   │   ├── ListProduct.php
│   │   ├── NewProduct.php
│   │   ├── Price.php
│   │   ├── ProductList
│   │   │   ├── Crosssell.php
│   │   │   ├── Item
│   │   │   │   ├── AddTo
│   │   │   │   │   └── Compare.php
│   │   │   │   ├── Block.php
│   │   │   │   └── Container.php
│   │   │   ├── Promotion.php
│   │   │   ├── Random.php
│   │   │   ├── Related.php
│   │   │   ├── Toolbar.php
│   │   │   └── Upsell.php
│   │   ├── ReviewRenderer
│   │   │   └── DefaultProvider.php
│   │   ├── ReviewRendererInterface.php
│   │   ├── TemplateSelector.php
│   │   ├── View
│   │   │   ├── AbstractView.php
│   │   │   ├── AddTo
│   │   │   │   └── Compare.php
│   │   │   ├── Additional.php
│   │   │   ├── Attributes.php
│   │   │   ├── BaseImage.php
│   │   │   ├── Description.php
│   │   │   ├── Details.php
│   │   │   ├── Gallery.php
│   │   │   ├── GalleryOptions.php
│   │   │   ├── Options
│   │   │   │   ├── AbstractOptions.php
│   │   │   │   └── Type
│   │   │   │       ├── Date.php
│   │   │   │       ├── DefaultType.php
│   │   │   │       ├── File.php
│   │   │   │       ├── Select
│   │   │   │       │   ├── Checkable.php
│   │   │   │       │   └── Multiple.php
│   │   │   │       ├── Select.php
│   │   │   │       └── Text.php
│   │   │   ├── Options.php
│   │   │   ├── Price.php
│   │   │   ├── Tabs.php
│   │   │   └── Type
│   │   │       ├── Simple.php
│   │   │       └── Virtual.php
│   │   ├── View.php
│   │   └── Widget
│   │       ├── Html
│   │       │   └── Pager.php
│   │       └── NewWidget.php
│   ├── Rss
│   │   ├── Category.php
│   │   └── Product
│   │       ├── NewProducts.php
│   │       └── Special.php
│   ├── ShortcutButtons.php
│   ├── ShortcutInterface.php
│   ├── Ui
│   │   └── ProductViewCounter.php
│   └── Widget
│       ├── Link.php
│       ├── RecentlyCompared.php
│       └── RecentlyViewed.php
├── Console
│   └── Command
│       └── ProductAttributesCleanUp.php
├── Controller
│   ├── Adminhtml
│   │   ├── Category
│   │   │   ├── Add.php
│   │   │   ├── CategoriesJson.php
│   │   │   ├── Delete.php
│   │   │   ├── Edit.php
│   │   │   ├── Grid.php
│   │   │   ├── Image
│   │   │   │   └── Upload.php
│   │   │   ├── Index.php
│   │   │   ├── Move.php
│   │   │   ├── RefreshPath.php
│   │   │   ├── Save.php
│   │   │   ├── SuggestCategories.php
│   │   │   ├── Tree.php
│   │   │   ├── Validate.php
│   │   │   ├── Widget
│   │   │   │   ├── CategoriesJson.php
│   │   │   │   └── Chooser.php
│   │   │   ├── Widget.php
│   │   │   └── Wysiwyg.php
│   │   ├── Category.php
│   │   ├── Product
│   │   │   ├── AbstractProductGrid.php
│   │   │   ├── Action
│   │   │   │   ├── Attribute
│   │   │   │   │   ├── Edit.php
│   │   │   │   │   ├── Save.php
│   │   │   │   │   └── Validate.php
│   │   │   │   └── Attribute.php
│   │   │   ├── AddAttributeToTemplate.php
│   │   │   ├── AlertsPriceGrid.php
│   │   │   ├── AlertsStockGrid.php
│   │   │   ├── Attribute
│   │   │   │   ├── Delete.php
│   │   │   │   ├── Edit.php
│   │   │   │   ├── Index.php
│   │   │   │   ├── NewAction.php
│   │   │   │   ├── Save.php
│   │   │   │   └── Validate.php
│   │   │   ├── Attribute.php
│   │   │   ├── Builder.php
│   │   │   ├── Categories.php
│   │   │   ├── Crosssell.php
│   │   │   ├── CrosssellGrid.php
│   │   │   ├── CustomOptions.php
│   │   │   ├── Datafeeds
│   │   │   │   └── Index.php
│   │   │   ├── Duplicate.php
│   │   │   ├── Edit.php
│   │   │   ├── Gallery
│   │   │   │   └── Upload.php
│   │   │   ├── GetSelected.php
│   │   │   ├── Grid.php
│   │   │   ├── GridOnly.php
│   │   │   ├── Group
│   │   │   │   └── Save.php
│   │   │   ├── Index.php
│   │   │   ├── Initialization
│   │   │   │   ├── Helper
│   │   │   │   │   ├── AttributeFilter.php
│   │   │   │   │   ├── HandlerFactory.php
│   │   │   │   │   ├── HandlerInterface.php
│   │   │   │   │   └── Plugin
│   │   │   │   │       └── Handler
│   │   │   │   │           └── Composite.php
│   │   │   │   ├── Helper.php
│   │   │   │   └── StockDataFilter.php
│   │   │   ├── MassDelete.php
│   │   │   ├── MassStatus.php
│   │   │   ├── NewAction.php
│   │   │   ├── Options.php
│   │   │   ├── OptionsImportGrid.php
│   │   │   ├── Related.php
│   │   │   ├── RelatedGrid.php
│   │   │   ├── Reload.php
│   │   │   ├── Save.php
│   │   │   ├── Search.php
│   │   │   ├── Set
│   │   │   │   ├── Add.php
│   │   │   │   ├── Delete.php
│   │   │   │   ├── Edit.php
│   │   │   │   ├── Index.php
│   │   │   │   ├── Save.php
│   │   │   │   └── SetGrid.php
│   │   │   ├── Set.php
│   │   │   ├── ShowUpdateResult.php
│   │   │   ├── SuggestAttributeSets.php
│   │   │   ├── SuggestAttributes.php
│   │   │   ├── Upsell.php
│   │   │   ├── UpsellGrid.php
│   │   │   ├── Validate.php
│   │   │   ├── Widget
│   │   │   │   └── Chooser.php
│   │   │   └── Wysiwyg.php
│   │   └── Product.php
│   ├── Category
│   │   └── View.php
│   ├── Index
│   │   └── Index.php
│   ├── Product
│   │   ├── Compare
│   │   │   ├── Add.php
│   │   │   ├── Clear.php
│   │   │   ├── Index.php
│   │   │   └── Remove.php
│   │   ├── Compare.php
│   │   ├── Frontend
│   │   │   └── Action
│   │   │       └── Synchronize.php
│   │   ├── Gallery.php
│   │   ├── View
│   │   │   └── ViewInterface.php
│   │   └── View.php
│   └── Product.php
├── Cron
│   ├── DeleteAbandonedStoreFlatTables.php
│   ├── DeleteOutdatedPriceValues.php
│   ├── FrontendActionsFlush.php
│   ├── RefreshSpecialPrices.php
│   └── SynchronizeWebsiteAttributes.php
├── CustomerData
│   ├── CompareProducts.php
│   ├── ProductFrontendActionSection.php
│   └── ProductsRenderInfoSection.php
├── Helper
│   ├── Catalog.php
│   ├── Category.php
│   ├── Data.php
│   ├── DefaultCategory.php
│   ├── Image.php
│   ├── Output.php
│   ├── Product
│   │   ├── Compare.php
│   │   ├── Composite.php
│   │   ├── Configuration
│   │   │   └── ConfigurationInterface.php
│   │   ├── Configuration.php
│   │   ├── ConfigurationPool.php
│   │   ├── Edit
│   │   │   └── Action
│   │   │       └── Attribute.php
│   │   ├── Flat
│   │   │   └── Indexer.php
│   │   ├── ProductList.php
│   │   └── View.php
│   └── Product.php
├── LICENSE.txt
├── LICENSE_AFL.txt
├── Model
│   ├── AbstractModel.php
│   ├── Api
│   │   └── SearchCriteria
│   │       └── CollectionProcessor
│   │           ├── ConditionProcessor
│   │           │   ├── ConditionBuilder
│   │           │   │   ├── EavAttributeCondition.php
│   │           │   │   ├── Factory.php
│   │           │   │   └── NativeAttributeCondition.php
│   │           │   ├── DefaultCondition.php
│   │           │   └── ProductCategoryCondition.php
│   │           └── FilterProcessor
│   │               ├── ProductCategoryFilter.php
│   │               ├── ProductPriceFilter.php
│   │               ├── ProductStoreFilter.php
│   │               └── ProductWebsiteFilter.php
│   ├── Attribute
│   │   ├── Backend
│   │   │   ├── AbstractLayoutUpdate.php
│   │   │   ├── Consumer.php
│   │   │   ├── ConsumerWebsiteAssign.php
│   │   │   ├── Customlayoutupdate.php
│   │   │   ├── DefaultBackend.php
│   │   │   ├── Startdate.php
│   │   │   └── WebsiteSpecific
│   │   │       ├── Scheduler.php
│   │   │       └── ValueSynchronizer.php
│   │   ├── Config
│   │   │   ├── Converter.php
│   │   │   ├── Data.php
│   │   │   ├── Reader.php
│   │   │   └── SchemaLocator.php
│   │   ├── Config.php
│   │   ├── LockValidatorComposite.php
│   │   ├── LockValidatorInterface.php
│   │   ├── ScopeOverriddenValue.php
│   │   └── Source
│   │       ├── AbstractLayoutUpdate.php
│   │       └── Scopes.php
│   ├── Category
│   │   ├── Attribute
│   │   │   ├── Backend
│   │   │   │   ├── Image.php
│   │   │   │   ├── LayoutUpdate.php
│   │   │   │   └── Sortby.php
│   │   │   ├── LayoutUpdateManager.php
│   │   │   ├── OptionManagement.php
│   │   │   └── Source
│   │   │       ├── Layout.php
│   │   │       ├── LayoutUpdate.php
│   │   │       ├── Mode.php
│   │   │       ├── Page.php
│   │   │       └── Sortby.php
│   │   ├── Attribute.php
│   │   ├── AttributeRepository.php
│   │   ├── Authorization.php
│   │   ├── DataProvider.php
│   │   ├── FileInfo.php
│   │   ├── Image.php
│   │   ├── Link
│   │   │   ├── ReadHandler.php
│   │   │   └── SaveHandler.php
│   │   ├── Product
│   │   │   └── PositionResolver.php
│   │   ├── StoreCategories.php
│   │   └── Tree.php
│   ├── Category.php
│   ├── CategoryAttributeSearchResults.php
│   ├── CategoryLink.php
│   ├── CategoryLinkManagement.php
│   ├── CategoryLinkRepository.php
│   ├── CategoryList.php
│   ├── CategoryManagement.php
│   ├── CategoryProductLink.php
│   ├── CategoryRepository
│   │   └── PopulateWithValues.php
│   ├── CategoryRepository.php
│   ├── CategorySearchResults.php
│   ├── CompareList.php
│   ├── CompareListIdToMaskedListId.php
│   ├── Config
│   │   ├── Backend
│   │   │   └── Category.php
│   │   ├── CatalogClone
│   │   │   └── Media
│   │   │       └── Image.php
│   │   ├── CatalogMediaConfig.php
│   │   ├── LayerCategoryConfig.php
│   │   └── Source
│   │       ├── Category.php
│   │       ├── GridPerPage.php
│   │       ├── LayoutList.php
│   │       ├── ListMode.php
│   │       ├── ListPerPage.php
│   │       ├── ListSort.php
│   │       ├── Price
│   │       │   ├── Scope.php
│   │       │   └── Step.php
│   │       ├── Product
│   │       │   ├── Options
│   │       │   │   ├── Price.php
│   │       │   │   ├── TierPrice.php
│   │       │   │   └── Type.php
│   │       │   └── Thumbnail.php
│   │       ├── ProductPriceOptionsInterface.php
│   │       ├── TimeFormat.php
│   │       ├── Watermark
│   │       │   └── Position.php
│   │       └── Web
│   │           └── CatalogMediaUrlFormat.php
│   ├── Config.php
│   ├── CustomOptions
│   │   ├── CustomOption.php
│   │   └── CustomOptionProcessor.php
│   ├── Design.php
│   ├── Entity
│   │   ├── Attribute.php
│   │   └── Product
│   │       └── Attribute
│   │           ├── Design
│   │           │   └── Options
│   │           │       └── Container.php
│   │           └── Group
│   │               ├── AttributeMapper.php
│   │               └── AttributeMapperInterface.php
│   ├── EntityInterface.php
│   ├── Factory.php
│   ├── FilterProductCustomAttribute.php
│   ├── FrontendStorageConfigurationInterface.php
│   ├── FrontendStorageConfigurationPool.php
│   ├── ImageExtractor.php
│   ├── ImageUploader.php
│   ├── Indexer
│   │   ├── AbstractFlatState.php
│   │   ├── Category
│   │   │   ├── Flat
│   │   │   │   ├── AbstractAction.php
│   │   │   │   ├── Action
│   │   │   │   │   ├── Full.php
│   │   │   │   │   └── Rows.php
│   │   │   │   ├── Plugin
│   │   │   │   │   ├── IndexerConfigData.php
│   │   │   │   │   ├── StoreGroup.php
│   │   │   │   │   └── StoreView.php
│   │   │   │   ├── SkipStaticColumnsProvider.php
│   │   │   │   ├── State.php
│   │   │   │   └── System
│   │   │   │       └── Config
│   │   │   │           └── Mode.php
│   │   │   ├── Flat.php
│   │   │   ├── Product
│   │   │   │   ├── AbstractAction.php
│   │   │   │   ├── Action
│   │   │   │   │   ├── Full.php
│   │   │   │   │   ├── Rows.php
│   │   │   │   │   └── RowsFactory.php
│   │   │   │   ├── Plugin
│   │   │   │   │   ├── MviewState.php
│   │   │   │   │   ├── StoreGroup.php
│   │   │   │   │   ├── StoreView.php
│   │   │   │   │   ├── TableResolver.php
│   │   │   │   │   └── Website.php
│   │   │   │   ├── Processor.php
│   │   │   │   ├── RowSizeEstimator.php
│   │   │   │   └── TableMaintainer.php
│   │   │   └── Product.php
│   │   └── Product
│   │       ├── Category
│   │       │   ├── Action
│   │       │   │   ├── Rows.php
│   │       │   │   └── RowsFactory.php
│   │       │   └── Processor.php
│   │       ├── Category.php
│   │       ├── Eav
│   │       │   ├── AbstractAction.php
│   │       │   ├── Action
│   │       │   │   ├── Full.php
│   │       │   │   ├── Row.php
│   │       │   │   └── Rows.php
│   │       │   ├── Plugin
│   │       │   │   ├── AttributeSet
│   │       │   │   │   └── IndexableAttributeFilter.php
│   │       │   │   ├── AttributeSet.php
│   │       │   │   └── StoreView.php
│   │       │   └── Processor.php
│   │       ├── Eav.php
│   │       ├── Flat
│   │       │   ├── AbstractAction.php
│   │       │   ├── Action
│   │       │   │   ├── Eraser.php
│   │       │   │   ├── Full.php
│   │       │   │   ├── Indexer.php
│   │       │   │   ├── Row.php
│   │       │   │   ├── Rows
│   │       │   │   │   └── TableData.php
│   │       │   │   └── Rows.php
│   │       │   ├── FlatTableBuilder.php
│   │       │   ├── Plugin
│   │       │   │   ├── IndexerConfigData.php
│   │       │   │   ├── Store.php
│   │       │   │   └── StoreGroup.php
│   │       │   ├── Processor.php
│   │       │   ├── State.php
│   │       │   ├── System
│   │       │   │   └── Config
│   │       │   │       └── Mode.php
│   │       │   ├── Table
│   │       │   │   ├── Builder.php
│   │       │   │   └── BuilderInterface.php
│   │       │   ├── TableBuilder.php
│   │       │   ├── TableData.php
│   │       │   └── TableDataInterface.php
│   │       ├── Flat.php
│   │       ├── Full.php
│   │       ├── Price
│   │       │   ├── AbstractAction.php
│   │       │   ├── Action
│   │       │   │   ├── Full.php
│   │       │   │   ├── Row.php
│   │       │   │   └── Rows.php
│   │       │   ├── DimensionCollectionFactory.php
│   │       │   ├── DimensionModeConfiguration.php
│   │       │   ├── InvalidateIndex.php
│   │       │   ├── ModeSwitcher.php
│   │       │   ├── ModeSwitcherConfiguration.php
│   │       │   ├── Plugin
│   │       │   │   ├── CustomerGroup.php
│   │       │   │   ├── TableResolver.php
│   │       │   │   └── Website.php
│   │       │   ├── PriceTableResolver.php
│   │       │   ├── Processor.php
│   │       │   ├── System
│   │       │   │   └── Config
│   │       │   │       └── PriceScope.php
│   │       │   ├── TableMaintainer.php
│   │       │   └── UpdateIndexInterface.php
│   │       └── Price.php
│   ├── Layer
│   │   ├── AvailabilityFlagInterface.php
│   │   ├── Category
│   │   │   ├── AvailabilityFlag.php
│   │   │   ├── CollectionFilter.php
│   │   │   ├── FilterableAttributeList.php
│   │   │   ├── ItemCollectionProvider.php
│   │   │   └── StateKey.php
│   │   ├── Category.php
│   │   ├── CollectionFilterInterface.php
│   │   ├── Context.php
│   │   ├── ContextInterface.php
│   │   ├── Filter
│   │   │   ├── AbstractFilter.php
│   │   │   ├── Attribute.php
│   │   │   ├── Category.php
│   │   │   ├── DataProvider
│   │   │   │   ├── Category.php
│   │   │   │   ├── Decimal.php
│   │   │   │   └── Price.php
│   │   │   ├── Decimal.php
│   │   │   ├── Dynamic
│   │   │   │   ├── AlgorithmFactory.php
│   │   │   │   ├── AlgorithmInterface.php
│   │   │   │   ├── Auto.php
│   │   │   │   ├── Improved.php
│   │   │   │   └── Manual.php
│   │   │   ├── Factory.php
│   │   │   ├── FilterInterface.php
│   │   │   ├── Item
│   │   │   │   └── DataBuilder.php
│   │   │   ├── Item.php
│   │   │   ├── Price
│   │   │   │   ├── Range.php
│   │   │   │   └── Render.php
│   │   │   └── Price.php
│   │   ├── FilterList.php
│   │   ├── FilterableAttributeListInterface.php
│   │   ├── ItemCollectionProviderInterface.php
│   │   ├── Resolver.php
│   │   ├── Search
│   │   │   ├── CollectionFilter.php
│   │   │   ├── Filter
│   │   │   │   └── Attribute.php
│   │   │   ├── FilterableAttributeList.php
│   │   │   └── ItemCollectionProvider.php
│   │   ├── Search.php
│   │   ├── State.php
│   │   └── StateKeyInterface.php
│   ├── Layer.php
│   ├── Layout
│   │   └── DepersonalizePlugin.php
│   ├── Locator
│   │   ├── LocatorInterface.php
│   │   └── RegistryLocator.php
│   ├── MaskedListIdToCompareListId.php
│   ├── Plugin
│   │   ├── Log.php
│   │   ├── ProductRepository
│   │   │   └── TransactionWrapper.php
│   │   ├── QuoteItemProductOption.php
│   │   ├── SetPageLayoutDefaultValue.php
│   │   └── ShowOutOfStockConfig.php
│   ├── Product
│   │   ├── Action.php
│   │   ├── Attribute
│   │   │   ├── AttributeSetFinder.php
│   │   │   ├── Backend
│   │   │   │   ├── Boolean.php
│   │   │   │   ├── Category.php
│   │   │   │   ├── GroupPrice
│   │   │   │   │   └── AbstractGroupPrice.php
│   │   │   │   ├── LayoutUpdate.php
│   │   │   │   ├── Media
│   │   │   │   │   ├── EntryConverterInterface.php
│   │   │   │   │   ├── EntryConverterPool.php
│   │   │   │   │   └── ImageEntryConverter.php
│   │   │   │   ├── Price.php
│   │   │   │   ├── Sku.php
│   │   │   │   ├── Stock.php
│   │   │   │   ├── TierPrice
│   │   │   │   │   ├── AbstractHandler.php
│   │   │   │   │   ├── SaveHandler.php
│   │   │   │   │   └── UpdateHandler.php
│   │   │   │   ├── Tierprice.php
│   │   │   │   └── Weight.php
│   │   │   ├── DataProvider.php
│   │   │   ├── DefaultAttributes.php
│   │   │   ├── Frontend
│   │   │   │   ├── Image.php
│   │   │   │   └── Inputtype
│   │   │   │       └── Presentation.php
│   │   │   ├── Group.php
│   │   │   ├── IsFilterableManagement.php
│   │   │   ├── LayoutUpdateManager.php
│   │   │   ├── Management.php
│   │   │   ├── OptionManagement.php
│   │   │   ├── Repository.php
│   │   │   ├── SetManagement.php
│   │   │   ├── SetRepository.php
│   │   │   ├── Source
│   │   │   │   ├── Boolean.php
│   │   │   │   ├── Countryofmanufacture.php
│   │   │   │   ├── Inputtype.php
│   │   │   │   ├── Layout.php
│   │   │   │   ├── LayoutUpdate.php
│   │   │   │   └── Status.php
│   │   │   ├── Type.php
│   │   │   └── TypesList.php
│   │   ├── AttributeSet
│   │   │   ├── Build.php
│   │   │   ├── Options.php
│   │   │   └── SuggestedSet.php
│   │   ├── Authorization.php
│   │   ├── CartConfiguration.php
│   │   ├── CatalogPrice.php
│   │   ├── CatalogPriceFactory.php
│   │   ├── CatalogPriceInterface.php
│   │   ├── Compare
│   │   │   ├── Item.php
│   │   │   └── ListCompare.php
│   │   ├── Condition
│   │   │   └── ConditionInterface.php
│   │   ├── Condition.php
│   │   ├── Configuration
│   │   │   └── Item
│   │   │       ├── ItemInterface.php
│   │   │       ├── ItemResolverComposite.php
│   │   │       ├── ItemResolverInterface.php
│   │   │       ├── Option
│   │   │       │   └── OptionInterface.php
│   │   │       └── Option.php
│   │   ├── Copier.php
│   │   ├── CopyConstructor
│   │   │   ├── Composite.php
│   │   │   ├── CrossSell.php
│   │   │   ├── Related.php
│   │   │   └── UpSell.php
│   │   ├── CopyConstructorFactory.php
│   │   ├── CopyConstructorInterface.php
│   │   ├── Edit
│   │   │   └── WeightResolver.php
│   │   ├── Exception.php
│   │   ├── Filter
│   │   │   └── DateTime.php
│   │   ├── Gallery
│   │   │   ├── CopyHandler.php
│   │   │   ├── CreateHandler.php
│   │   │   ├── DeleteHandler.php
│   │   │   ├── DeleteValidator.php
│   │   │   ├── Entry.php
│   │   │   ├── EntryResolver.php
│   │   │   ├── GalleryManagement.php
│   │   │   ├── ImagesConfigFactory.php
│   │   │   ├── ImagesConfigFactoryInterface.php
│   │   │   ├── MimeTypeExtensionMap.php
│   │   │   ├── Processor.php
│   │   │   ├── ReadHandler.php
│   │   │   └── UpdateHandler.php
│   │   ├── Hydrator.php
│   │   ├── Image
│   │   │   ├── Cache.php
│   │   │   ├── ConvertImageMiscParamsToReadableFormat.php
│   │   │   ├── NotLoadInfoImageException.php
│   │   │   ├── ParamsBuilder.php
│   │   │   ├── RemoveDeletedImagesFromCache.php
│   │   │   └── UrlBuilder.php
│   │   ├── Image.php
│   │   ├── Initialization
│   │   │   └── Helper
│   │   │       └── ProductLinks.php
│   │   ├── Link
│   │   │   ├── Converter.php
│   │   │   ├── Resolver.php
│   │   │   └── SaveHandler.php
│   │   ├── Link.php
│   │   ├── LinkTypeProvider.php
│   │   ├── Media
│   │   │   ├── AttributeManagement.php
│   │   │   ├── Config.php
│   │   │   └── ConfigInterface.php
│   │   ├── Option
│   │   │   ├── Converter.php
│   │   │   ├── ReadHandler.php
│   │   │   ├── Repository.php
│   │   │   ├── SaveHandler.php
│   │   │   ├── Type
│   │   │   │   ├── Date.php
│   │   │   │   ├── DefaultType.php
│   │   │   │   ├── Factory.php
│   │   │   │   ├── File
│   │   │   │   │   ├── ExistingValidate.php
│   │   │   │   │   ├── RequestAwareValidatorFile.php
│   │   │   │   │   ├── ValidateFactory.php
│   │   │   │   │   ├── Validator.php
│   │   │   │   │   ├── ValidatorFile.php
│   │   │   │   │   └── ValidatorInfo.php
│   │   │   │   ├── File.php
│   │   │   │   ├── Select.php
│   │   │   │   └── Text.php
│   │   │   ├── Type.php
│   │   │   ├── UrlBuilder.php
│   │   │   ├── Validator
│   │   │   │   ├── DefaultValidator.php
│   │   │   │   ├── File.php
│   │   │   │   ├── Pool.php
│   │   │   │   ├── Select.php
│   │   │   │   └── Text.php
│   │   │   └── Value.php
│   │   ├── Option.php
│   │   ├── Price
│   │   │   ├── BasePrice.php
│   │   │   ├── BasePriceStorage.php
│   │   │   ├── Cost.php
│   │   │   ├── CostStorage.php
│   │   │   ├── PricePersistence.php
│   │   │   ├── PriceUpdateResult.php
│   │   │   ├── SpecialPrice.php
│   │   │   ├── SpecialPriceStorage.php
│   │   │   ├── TierPrice.php
│   │   │   ├── TierPriceFactory.php
│   │   │   ├── TierPricePersistence.php
│   │   │   ├── TierPriceStorage.php
│   │   │   └── Validation
│   │   │       ├── InvalidSkuProcessor.php
│   │   │       ├── Result.php
│   │   │       └── TierPriceValidator.php
│   │   ├── PriceModifier
│   │   │   └── Composite.php
│   │   ├── PriceModifier.php
│   │   ├── PriceModifierInterface.php
│   │   ├── Pricing
│   │   │   └── Renderer
│   │   │       ├── SalableResolver.php
│   │   │       └── SalableResolverInterface.php
│   │   ├── ProductFrontendAction
│   │   │   └── Synchronizer.php
│   │   ├── ProductList
│   │   │   ├── Toolbar.php
│   │   │   └── ToolbarMemorizer.php
│   │   ├── ReservedAttributeCheckerAdapter.php
│   │   ├── ReservedAttributeList.php
│   │   ├── ScopedTierPriceManagement.php
│   │   ├── TierPrice.php
│   │   ├── TierPriceManagement.php
│   │   ├── Type
│   │   │   ├── AbstractType.php
│   │   │   ├── FrontSpecialPrice.php
│   │   │   ├── Pool.php
│   │   │   ├── Price
│   │   │   │   └── Factory.php
│   │   │   ├── Price.php
│   │   │   ├── Simple.php
│   │   │   └── Virtual.php
│   │   ├── Type.php
│   │   ├── TypeTransitionManager.php
│   │   ├── Url.php
│   │   ├── Validator.php
│   │   ├── Visibility.php
│   │   ├── Webapi
│   │   │   ├── ProductOutputProcessor.php
│   │   │   └── Rest
│   │   │       └── RequestTypeBasedDeserializer.php
│   │   ├── Website
│   │   │   ├── ReadHandler.php
│   │   │   └── SaveHandler.php
│   │   └── Website.php
│   ├── Product.php
│   ├── ProductAttributeGroupRepository.php
│   ├── ProductAttributeSearchResults.php
│   ├── ProductCategoryList.php
│   ├── ProductFrontendAction.php
│   ├── ProductIdLocator.php
│   ├── ProductIdLocatorInterface.php
│   ├── ProductLink
│   │   ├── Attribute.php
│   │   ├── CollectionProvider
│   │   │   ├── Crosssell.php
│   │   │   ├── LinkedMapProvider.php
│   │   │   ├── Related.php
│   │   │   └── Upsell.php
│   │   ├── CollectionProvider.php
│   │   ├── CollectionProviderInterface.php
│   │   ├── Converter
│   │   │   ├── ConverterInterface.php
│   │   │   ├── ConverterPool.php
│   │   │   └── DefaultConverter.php
│   │   ├── Data
│   │   │   ├── ListCriteria.php
│   │   │   ├── ListCriteriaInterface.php
│   │   │   ├── ListResult.php
│   │   │   └── ListResultInterface.php
│   │   ├── Link.php
│   │   ├── Management.php
│   │   ├── MapProviderInterface.php
│   │   ├── ProductLinkQuery.php
│   │   ├── Repository.php
│   │   ├── Search.php
│   │   └── Type.php
│   ├── ProductManagement.php
│   ├── ProductNotFoundPageCacheTags.php
│   ├── ProductOption.php
│   ├── ProductOptionProcessor.php
│   ├── ProductOptionProcessorInterface.php
│   ├── ProductOptions
│   │   ├── Config
│   │   │   ├── Converter.php
│   │   │   ├── Reader.php
│   │   │   └── SchemaLocator.php
│   │   ├── Config.php
│   │   ├── ConfigInterface.php
│   │   └── TypeList.php
│   ├── ProductRender
│   │   ├── Button.php
│   │   ├── FormattedPriceInfo.php
│   │   ├── FormattedPriceInfoBuilder.php
│   │   ├── Image.php
│   │   └── PriceInfo.php
│   ├── ProductRender.php
│   ├── ProductRenderInfoSearchResults.php
│   ├── ProductRenderList.php
│   ├── ProductRepository
│   │   └── MediaGalleryProcessor.php
│   ├── ProductRepository.php
│   ├── ProductSearchResults.php
│   ├── ProductType.php
│   ├── ProductTypeList.php
│   ├── ProductTypes
│   │   ├── Config
│   │   │   ├── Converter.php
│   │   │   ├── Reader.php
│   │   │   └── SchemaLocator.php
│   │   ├── Config.php
│   │   └── ConfigInterface.php
│   ├── ProductVisibilityCondition.php
│   ├── ProductWebsiteLink.php
│   ├── ProductWebsiteLinkRepository.php
│   ├── ResourceModel
│   │   ├── AbstractCollection.php
│   │   ├── AbstractResource.php
│   │   ├── Attribute
│   │   │   ├── ConditionBuilder.php
│   │   │   ├── RemoveProductAttributeData.php
│   │   │   └── WebsiteAttributesSynchronizer.php
│   │   ├── Attribute.php
│   │   ├── AttributePersistor.php
│   │   ├── Category
│   │   │   ├── AggregateCount.php
│   │   │   ├── Attribute
│   │   │   │   ├── Collection.php
│   │   │   │   ├── Frontend
│   │   │   │   │   └── Image.php
│   │   │   │   └── Source
│   │   │   │       ├── Layout.php
│   │   │   │       └── Page.php
│   │   │   ├── Collection
│   │   │   │   └── Factory.php
│   │   │   ├── Collection.php
│   │   │   ├── Flat
│   │   │   │   └── Collection.php
│   │   │   ├── Flat.php
│   │   │   ├── StateDependentCollectionFactory.php
│   │   │   └── Tree.php
│   │   ├── Category.php
│   │   ├── CategoryProduct.php
│   │   ├── Collection
│   │   │   └── AbstractCollection.php
│   │   ├── Config.php
│   │   ├── DuplicatedProductAttributesCopier.php
│   │   ├── Eav
│   │   │   └── Attribute.php
│   │   ├── GetProductTypeById.php
│   │   ├── Helper.php
│   │   ├── Indexer
│   │   │   └── ActiveTableSwitcher.php
│   │   ├── Layer
│   │   │   └── Filter
│   │   │       ├── Attribute.php
│   │   │       ├── Decimal.php
│   │   │       └── Price.php
│   │   ├── MaxHeapTableSizeProcessor.php
│   │   ├── MediaImageDeleteProcessor.php
│   │   ├── Product
│   │   │   ├── Action.php
│   │   │   ├── Attribute
│   │   │   │   ├── Backend
│   │   │   │   │   ├── GroupPrice
│   │   │   │   │   │   └── AbstractGroupPrice.php
│   │   │   │   │   ├── Image.php
│   │   │   │   │   └── Tierprice.php
│   │   │   │   └── Collection.php
│   │   │   ├── BaseSelectProcessorInterface.php
│   │   │   ├── CategoryLink.php
│   │   │   ├── Collection
│   │   │   │   ├── JoinMinimalPosition.php
│   │   │   │   └── ProductLimitation.php
│   │   │   ├── Collection.php
│   │   │   ├── Compare
│   │   │   │   ├── CompareList.php
│   │   │   │   ├── Item
│   │   │   │   │   └── Collection.php
│   │   │   │   └── Item.php
│   │   │   ├── CompositeBaseSelectProcessor.php
│   │   │   ├── Flat.php
│   │   │   ├── Gallery.php
│   │   │   ├── Image.php
│   │   │   ├── Indexer
│   │   │   │   ├── AbstractIndexer.php
│   │   │   │   ├── Eav
│   │   │   │   │   ├── AbstractEav.php
│   │   │   │   │   ├── BatchSizeCalculator.php
│   │   │   │   │   ├── Decimal.php
│   │   │   │   │   ├── DecimalRowSizeEstimator.php
│   │   │   │   │   ├── Source.php
│   │   │   │   │   └── SourceRowSizeEstimator.php
│   │   │   │   ├── LinkedProductSelectBuilderByIndexPrice.php
│   │   │   │   ├── Price
│   │   │   │   │   ├── BasePriceModifier.php
│   │   │   │   │   ├── BatchSizeCalculator.php
│   │   │   │   │   ├── CompositeProductBatchSizeAdjuster.php
│   │   │   │   │   ├── CompositeProductBatchSizeAdjusterInterface.php
│   │   │   │   │   ├── CompositeProductRelationsCalculator.php
│   │   │   │   │   ├── CompositeProductRowSizeEstimator.php
│   │   │   │   │   ├── CustomOptionPriceModifier.php
│   │   │   │   │   ├── DefaultPrice.php
│   │   │   │   │   ├── Factory.php
│   │   │   │   │   ├── IndexTableRowSizeEstimator.php
│   │   │   │   │   ├── IndexTableStructure.php
│   │   │   │   │   ├── PriceInterface.php
│   │   │   │   │   ├── PriceModifierInterface.php
│   │   │   │   │   ├── Query
│   │   │   │   │   │   ├── BaseFinalPrice.php
│   │   │   │   │   │   └── JoinAttributeProcessor.php
│   │   │   │   │   ├── SimpleProductPrice.php
│   │   │   │   │   └── TierPrice.php
│   │   │   │   └── TemporaryTableStrategy.php
│   │   │   ├── Link
│   │   │   │   ├── Collection.php
│   │   │   │   ├── DeleteHandler.php
│   │   │   │   ├── Product
│   │   │   │   │   └── Collection.php
│   │   │   │   └── SaveHandler.php
│   │   │   ├── Link.php
│   │   │   ├── LinkedProductSelectBuilderByBasePrice.php
│   │   │   ├── LinkedProductSelectBuilderBySpecialPrice.php
│   │   │   ├── LinkedProductSelectBuilderByTierPrice.php
│   │   │   ├── LinkedProductSelectBuilderComposite.php
│   │   │   ├── LinkedProductSelectBuilderInterface.php
│   │   │   ├── Option
│   │   │   │   ├── Collection.php
│   │   │   │   ├── Value
│   │   │   │   │   └── Collection.php
│   │   │   │   └── Value.php
│   │   │   ├── Option.php
│   │   │   ├── Price
│   │   │   │   └── SpecialPrice.php
│   │   │   ├── Relation.php
│   │   │   ├── StatusBaseSelectProcessor.php
│   │   │   ├── Website
│   │   │   │   ├── Link.php
│   │   │   │   └── SelectProcessor.php
│   │   │   └── Website.php
│   │   ├── Product.php
│   │   ├── ProductFrontendAction
│   │   │   └── Collection.php
│   │   ├── ProductFrontendAction.php
│   │   ├── ProductWebsiteAssignmentHandler.php
│   │   ├── Setup
│   │   │   └── PropertyMapper.php
│   │   └── Url.php
│   ├── Rss
│   │   ├── Category.php
│   │   └── Product
│   │       ├── NewProducts.php
│   │       ├── NotifyStock.php
│   │       └── Special.php
│   ├── Session.php
│   ├── System
│   │   └── Config
│   │       ├── Backend
│   │       │   ├── Catalog
│   │       │   │   └── Url
│   │       │   │       └── Rewrite
│   │       │   │           └── Suffix.php
│   │       │   └── Rss
│   │       │       └── Category.php
│   │       └── Source
│   │           └── Inputtype.php
│   ├── Template
│   │   ├── Filter
│   │   │   └── Factory.php
│   │   └── Filter.php
│   ├── Theme
│   │   └── CustomerData
│   │       └── MessagesProvider.php
│   ├── View
│   │   └── Asset
│   │       ├── Image
│   │       │   └── Context.php
│   │       ├── Image.php
│   │       └── Placeholder.php
│   ├── Webapi
│   │   └── Product
│   │       └── Option
│   │           └── Type
│   │               ├── Date.php
│   │               └── File
│   │                   └── Processor.php
│   └── Widget
│       ├── RecentlyComparedStorageConfiguration.php
│       └── RecentlyViewedStorageConfiguration.php
├── Observer
│   ├── CatalogCheckIsUsingStaticUrlsAllowedObserver.php
│   ├── CategoryDesignAuthorization.php
│   ├── CategoryProductIndexer.php
│   ├── Compare
│   │   ├── BindCustomerLoginObserver.php
│   │   └── BindCustomerLogoutObserver.php
│   ├── FlushCategoryPagesCache.php
│   ├── ImageResizeAfterProductSave.php
│   ├── InvalidateCacheOnCategoryDesignChange.php
│   ├── MenuCategoryData.php
│   ├── SetSpecialPriceStartDate.php
│   ├── SwitchPriceAttributeScopeOnConfigChange.php
│   └── SynchronizeWebsiteAttributesOnStoreChange.php
├── Plugin
│   ├── Api
│   │   └── ProductLinkRepositoryInterface
│   │       ├── ReindexAfterDeleteByIdProductLinksPlugin.php
│   │       └── ReindexAfterSaveProductLinksPlugin.php
│   ├── Block
│   │   └── Topmenu.php
│   ├── CategoryAuthorization.php
│   ├── Framework
│   │   └── App
│   │       └── Action
│   │           └── ContextPlugin.php
│   ├── Model
│   │   ├── Attribute
│   │   │   └── Backend
│   │   │       └── AttributeValidation.php
│   │   ├── AttributeSetRepository
│   │   │   └── RemoveProducts.php
│   │   ├── Indexer
│   │   │   └── Category
│   │   │       └── Product
│   │   │           ├── Execute.php
│   │   │           └── MaxHeapTableSizeProcessorOnFullReindex.php
│   │   ├── Product
│   │   │   ├── Action
│   │   │   │   └── UpdateAttributesFlushCache.php
│   │   │   └── Option
│   │   │       └── UpdateProductCustomOptionsAttributes.php
│   │   └── ResourceModel
│   │       ├── Attribute
│   │       │   └── Save.php
│   │       ├── Config.php
│   │       └── ReadSnapshotPlugin.php
│   ├── ProductAuthorization.php
│   ├── RemoveImagesFromGalleryAfterRemovingProduct.php
│   └── Ui
│       └── DataProvider
│           └── Product
│               └── ProductDataProvider.php
├── Pricing
│   ├── Price
│   │   ├── BasePrice.php
│   │   ├── CalculateCustomOptionCatalogRule.php
│   │   ├── Collection.php
│   │   ├── ConfiguredOptions.php
│   │   ├── ConfiguredPrice.php
│   │   ├── ConfiguredPriceInterface.php
│   │   ├── ConfiguredPriceSelection.php
│   │   ├── ConfiguredRegularPrice.php
│   │   ├── CustomOptionPrice.php
│   │   ├── CustomOptionPriceCalculator.php
│   │   ├── CustomOptionPriceInterface.php
│   │   ├── FinalPrice.php
│   │   ├── FinalPriceInterface.php
│   │   ├── MinimalPriceCalculatorInterface.php
│   │   ├── MinimalTierPriceCalculator.php
│   │   ├── RegularPrice.php
│   │   ├── SpecialPrice.php
│   │   ├── SpecialPriceInterface.php
│   │   ├── TierPrice.php
│   │   └── TierPriceInterface.php
│   ├── Render
│   │   ├── ConfiguredPriceBox.php
│   │   ├── FinalPriceBox.php
│   │   └── PriceBox.php
│   └── Render.php
├── README.md
├── Setup
│   ├── CategorySetup.php
│   ├── Patch
│   │   ├── Data
│   │   │   ├── ChangePriceAttributeDefaultScope.php
│   │   │   ├── DisallowUsingHtmlForProductName.php
│   │   │   ├── EnableDirectiveParsing.php
│   │   │   ├── EnableSegmentation.php
│   │   │   ├── InstallDefaultCategories.php
│   │   │   ├── SetNewResourceModelsPaths.php
│   │   │   ├── UpdateCustomLayoutAttributes.php
│   │   │   ├── UpdateDefaultAttributeValue.php
│   │   │   ├── UpdateMediaAttributesBackendTypes.php
│   │   │   ├── UpdateMultiselectAttributesBackendTypes.php
│   │   │   ├── UpdateProductAttributes.php
│   │   │   ├── UpdateProductDescriptionOrder.php
│   │   │   ├── UpdateProductMetaDescription.php
│   │   │   ├── UpdateProductUrlKey.php
│   │   │   ├── UpgradeWebsiteAttributes.php
│   │   │   └── UpgradeWidgetData.php
│   │   └── Schema
│   │       └── EnableSegmentation.php
│   └── Recurring.php
├── Test
│   ├── Fixture
│   │   ├── AssignProducts.php
│   │   ├── Attribute.php
│   │   ├── AttributeSet.php
│   │   ├── Category.php
│   │   ├── CategoryAttribute.php
│   │   ├── MultiselectAttribute.php
│   │   ├── Product.php
│   │   ├── ProductStock.php
│   │   ├── SelectAttribute.php
│   │   └── Virtual.php
│   ├── Mftf
│   │   ├── ActionGroup
│   │   │   ├── AddCategoryImageActionGroup.xml
│   │   │   ├── AddCostPriceToProductActionGroup.xml
│   │   │   ├── AddCrossSellProductBySkuActionGroup.xml
│   │   │   ├── AddProductAttributeInProductModalActionGroup.xml
│   │   │   ├── AddProductCustomOptionFieldActionGroup.xml
│   │   │   ├── AddProductCustomOptionFileActionGroup.xml
│   │   │   ├── AddProductImageActionGroup.xml
│   │   │   ├── AddProductWithQtyToCartFromStorefrontProductPageActionGroup.xml
│   │   │   ├── AddRelatedProductBySkuActionGroup.xml
│   │   │   ├── AddSimpleProductToCartActionGroup.xml
│   │   │   ├── AddSpecialPriceToProductActionGroup.xml
│   │   │   ├── AddToCartFromStorefrontProductPageActionGroup.xml
│   │   │   ├── AddUpSellProductBySkuActionGroup.xml
│   │   │   ├── AddWebsiteToProductActionGroup.xml
│   │   │   ├── AdminAddAdvancedPricingToTheProductActionGroup.xml
│   │   │   ├── AdminAddAdvancedPricingToTheProductExtendedActionGroup.xml
│   │   │   ├── AdminAddCustomAttributeToSelectedProductActionGroup.xml
│   │   │   ├── AdminAddMinimumAdvertisedPriceActionGroup.xml
│   │   │   ├── AdminAddMultipleSimpleProductToBundleProductActionGroup.xml
│   │   │   ├── AdminAddOptionForDropdownAttributeActionGroup.xml
│   │   │   ├── AdminAddOptionToBundleProductActionGroup.xml
│   │   │   ├── AdminAddProductCustomOptionActionGroup.xml
│   │   │   ├── AdminAddProductToCategoryActionGroup.xml
│   │   │   ├── AdminAddTitleAndPriceValueToCustomOptionActionGroup.xml
│   │   │   ├── AdminAddUnassignedAttributeToGroupActionGroup.xml
│   │   │   ├── AdminAllIndexerSetUpdateOnSaveActionGroup.xml
│   │   │   ├── AdminAnchorCategoryActionGroup.xml
│   │   │   ├── AdminAssertParentChildCategoryTreeElementsActionGroup.xml
│   │   │   ├── AdminAssertProductAttributeInAttributeGridActionGroup.xml
│   │   │   ├── AdminAssertProductAttributeOnProductEditPageActionGroup.xml
│   │   │   ├── AdminAssertProductCustomOptionVisibleActionGroup.xml
│   │   │   ├── AdminAssertProductEditPageCreateAttributeSaveInAttributeSetPopUpShownActionGroup.xml
│   │   │   ├── AdminAssertProductHasNoCustomOptionActionGroup.xml
│   │   │   ├── AdminAssertProductHasNoCustomOptionsActionGroup.xml
│   │   │   ├── AdminAssertProductImageOnProductPageActionGroup.xml
│   │   │   ├── AdminAssertProductInfoOnEditPageActionGroup.xml
│   │   │   ├── AdminAssertProductsGridIsEmptyActionGroup.xml
│   │   │   ├── AdminAssignCategoryToProductAndSaveActionGroup.xml
│   │   │   ├── AdminAssignImageBaseRoleActionGroup.xml
│   │   │   ├── AdminAssignImageRolesActionGroup.xml
│   │   │   ├── AdminAssignImageRolesIfUnassignedActionGroup.xml
│   │   │   ├── AdminAssignImageSmallRoleActionGroup.xml
│   │   │   ├── AdminAssignImageThumbNailRoleActionGroup.xml
│   │   │   ├── AdminAssignProductInWebsiteActionGroup.xml
│   │   │   ├── AdminAssignProductToCategoryActionGroup.xml
│   │   │   ├── AdminAssignTwoCategoriesToProductActionGroup.xml
│   │   │   ├── AdminCategoriesExpandAllActionGroup.xml
│   │   │   ├── AdminCategoriesOpenCategoryActionGroup.xml
│   │   │   ├── AdminCategoriesOpenContentSectionActionGroup.xml
│   │   │   ├── AdminCategoriesSetDisplayModeActionGroup.xml
│   │   │   ├── AdminCategoriesSetStaticBlockActionGroup.xml
│   │   │   ├── AdminCategoryAssignProductActionGroup.xml
│   │   │   ├── AdminCategoryOpenDesignSectionActionGroup.xml
│   │   │   ├── AdminCategoryOpenScheduleDesignUpdateSectionActionGroup.xml
│   │   │   ├── AdminCategoryPageOpenProductsInCategorySectionActionGroup.xml
│   │   │   ├── AdminChangeCategoryAndURLNameActionGroup.xml
│   │   │   ├── AdminChangeCategoryNameActionGroup.xml
│   │   │   ├── AdminChangeCategoryNameOnStoreViewLevelActionGroup.xml
│   │   │   ├── AdminChangeProductSEOSettingsActionGroup.xml
│   │   │   ├── AdminChangeSeoUrlKeyForSubCategoryWithoutRedirectActionGroup.xml
│   │   │   ├── AdminChangeSeoUrlKeyToDefaultValueWithoutRedirectActionGroup.xml
│   │   │   ├── AdminChangeWebSiteAssignedToProductActionGroup.xml
│   │   │   ├── AdminCheckFirstCheckboxInAddProductsToOptionPanelGridActionGroup.xml
│   │   │   ├── AdminCheckNameToggleOnProductsMassAttributeUpdateActionGroup.xml
│   │   │   ├── AdminCheckProductByIdOnProductGridActionGroup.xml
│   │   │   ├── AdminCheckProductIsMissingInCategoryProductsGridActionGroup.xml
│   │   │   ├── AdminCheckProductOnProductGridActionGroup.xml
│   │   │   ├── AdminCheckProductPositionInCategoryProductsGridActionGroup.xml
│   │   │   ├── AdminClickAddAttributeOnProductEditPageActionGroup.xml
│   │   │   ├── AdminClickAddProductToggleAndSelectProductTypeActionGroup.xml
│   │   │   ├── AdminClickAddSelectedProductsOnAddProductsToOptionPanelActionGroup.xml
│   │   │   ├── AdminClickAddSubcategoryButtonActionGroup.xml
│   │   │   ├── AdminClickCreateNewAttributeFromProductEditPageActionGroup.xml
│   │   │   ├── AdminClickMassUpdateProductAttributesActionGroup.xml
│   │   │   ├── AdminClickOnAdvancedInventoryButtonActionGroup.xml
│   │   │   ├── AdminClickOnAdvancedInventoryLinkActionGroup.xml
│   │   │   ├── AdminClickSaveOnProductsMassAttributeUpdateActionGroup.xml
│   │   │   ├── AdminCreateAttributeFromProductPageActionGroup.xml
│   │   │   ├── AdminCreateAttributeFromProductPageWithScopeActionGroup.xml
│   │   │   ├── AdminCreateAttributeTextSwatchNthValueActionGroup.xml
│   │   │   ├── AdminCreateAttributeVisualSwatchNthValueActionGroup.xml
│   │   │   ├── AdminCreateAttributeWithSearchWeightActionGroup.xml
│   │   │   ├── AdminCreateAttributeWithValueWithTwoStoreViesFromProductPageActionGroup.xml
│   │   │   ├── AdminCreateCatalogProductWidgetActionGroup.xml
│   │   │   ├── AdminCreateCategoryWithInactiveIncludeInMenuActionGroup.xml
│   │   │   ├── AdminCreateCustomDropDownOptionsActionGroup.xml
│   │   │   ├── AdminCreateCustomGroupInAnAttriubuteSetActionGroup.xml
│   │   │   ├── AdminCreateInactiveCategoryActionGroup.xml
│   │   │   ├── AdminCreateRecentlyProductsWidgetActionGroup.xml
│   │   │   ├── AdminCreateRootCategoryActionGroup.xml
│   │   │   ├── AdminCreateSearchableProductAttributeActionGroup.xml
│   │   │   ├── AdminCreateSimpleProductActionGroup.xml
│   │   │   ├── AdminCreateSimpleProductWithTextOptionCharLimitActionGroup.xml
│   │   │   ├── AdminDeleteAllProductAttributesFilteredByCodeActionGroup.xml
│   │   │   ├── AdminDeleteAllProductsFromGridActionGroup.xml
│   │   │   ├── AdminDeleteCategoryByNameActionGroup.xml
│   │   │   ├── AdminDeleteCreatedColorSpecificAttributeActionGroup.xml
│   │   │   ├── AdminDeleteCustomGroupDragAndDropAttributesInAnAttributeSetActionGroup.xml
│   │   │   ├── AdminDeleteProductAttributeByLabelActionGroup.xml
│   │   │   ├── AdminDeleteProductCustomOptionActionGroup.xml
│   │   │   ├── AdminDisableActiveCategoryActionGroup.xml
│   │   │   ├── AdminDisableIncludeInMenuConfigActionGroup.xml
│   │   │   ├── AdminEnableCategoryActionGroup.xml
│   │   │   ├── AdminExpandCategoryTreeActionGroup.xml
│   │   │   ├── AdminExpandProductAttributesTabActionGroup.xml
│   │   │   ├── AdminExpandProductDesignSectionActionGroup.xml
│   │   │   ├── AdminFillAdvancedInventoryOutOfStockThresholdActionGroup.xml
│   │   │   ├── AdminFillAdvancedInventoryQtyActionGroup.xml
│   │   │   ├── AdminFillAttributeDataProductFormNewAttributeActionGroup.xml
│   │   │   ├── AdminFillInProductDescriptionActionGroup.xml
│   │   │   ├── AdminFillInProductShortDescriptionActionGroup.xml
│   │   │   ├── AdminFillMainProductFormActionGroup.xml
│   │   │   ├── AdminFillProductAttributeDefaultStoreViewActionGroup.xml
│   │   │   ├── AdminFillProductAttributePropertiesActionGroup.xml
│   │   │   ├── AdminFillProductCountryOfManufactureActionGroup.xml
│   │   │   ├── AdminFillProductNameOnProductFormActionGroup.xml
│   │   │   ├── AdminFillProductPriceFieldAndPressEnterOnProductEditPageActionGroup.xml
│   │   │   ├── AdminFillProductQtyOnProductFormActionGroup.xml
│   │   │   ├── AdminFillProductSkuOnProductFormActionGroup.xml
│   │   │   ├── AdminIncludeInMenuExcludedCategoryActionGroup.xml
│   │   │   ├── AdminInputCustomAttributeToExistingProductActionGroup.xml
│   │   │   ├── AdminMassUpdateProductAttributeActionGroup.xml
│   │   │   ├── AdminMassUpdateProductAttributeSaveActionGroup.xml
│   │   │   ├── AdminMassUpdateProductQtyAndStockStatusActionGroup.xml
│   │   │   ├── AdminMassUpdateProductQtyIncrementsActionGroup.xml
│   │   │   ├── AdminNavigateToNewProductAttributePageActionGroup.xml
│   │   │   ├── AdminNavigateToProductAttributeAdvancedSectionActionGroup.xml
│   │   │   ├── AdminNavigateToProductAttributeEditPageActionGroup.xml
│   │   │   ├── AdminOpenAndApplyCustomOptionRecordsPerPageActionGroup.xml
│   │   │   ├── AdminOpenAndApplyCustomOptionsPerPageActionGroup.xml
│   │   │   ├── AdminOpenAttributeSetByNameActionGroup.xml
│   │   │   ├── AdminOpenAttributeSetGridPageActionGroup.xml
│   │   │   ├── AdminOpenCatalogProductPageActionGroup.xml
│   │   │   ├── AdminOpenCategoryPageActionGroup.xml
│   │   │   ├── AdminOpenContentSectionOnProductPageActionGroup.xml
│   │   │   ├── AdminOpenCreateNewWidgetsOfCMSStaticBlockActionGroup.xml
│   │   │   ├── AdminOpenNewProductFormPageActionGroup.xml
│   │   │   ├── AdminOpenProductAttributePageActionGroup.xml
│   │   │   ├── AdminOpenProductImagesSectionActionGroup.xml
│   │   │   ├── AdminOpenProductIndexPageActionGroup.xml
│   │   │   ├── AdminProcessProductWebsitesActionGroup.xml
│   │   │   ├── AdminProductAddSpecialPriceActionGroup.xml
│   │   │   ├── AdminProductAdvancedPricingNewCustomerGroupPriceActionGroup.xml
│   │   │   ├── AdminProductAssertImageAltTextActionGroup.xml
│   │   │   ├── AdminProductAttributeMassUpdateActionGroup.xml
│   │   │   ├── AdminProductAttributePageSwitchTabActionGroup.xml
│   │   │   ├── AdminProductAttributeSaveActionGroup.xml
│   │   │   ├── AdminProductAttributeSetActionGroup.xml
│   │   │   ├── AdminProductAttributeSetVisibleInAdvancedSearchActionGroup.xml
│   │   │   ├── AdminProductCatalogPageOpenActionGroup.xml
│   │   │   ├── AdminProductChangeImageAltTextActionGroup.xml
│   │   │   ├── AdminProductFormAdvancedPricingAddTierPriceActionGroup.xml
│   │   │   ├── AdminProductFormCategoryExistInCategoryListActionGroup.xml
│   │   │   ├── AdminProductFormCategoryNotExistInCategoryListActionGroup.xml
│   │   │   ├── AdminProductFormCloseAdvancedPricingDialogActionGroup.xml
│   │   │   ├── AdminProductFormDoneAdvancedPricingDialogActionGroup.xml
│   │   │   ├── AdminProductFormOpenAdvancedPricingDialogActionGroup.xml
│   │   │   ├── AdminProductFormSaveActionGroup.xml
│   │   │   ├── AdminProductFormSaveButtonClickActionGroup.xml
│   │   │   ├── AdminProductGridSectionClickFirstRowActionGroup.xml
│   │   │   ├── AdminProductPageCreateAttributeSetWithAttributeActionGroup.xml
│   │   │   ├── AdminProductPageFillTextAttributeValueByNameActionGroup.xml
│   │   │   ├── AdminProductPageOpenByIdActionGroup.xml
│   │   │   ├── AdminProductPageSelectAttributeSetActionGroup.xml
│   │   │   ├── AdminSaveCategoryActionGroup.xml
│   │   │   ├── AdminSaveCategoryFormActionGroup.xml
│   │   │   ├── AdminSaveProductAttributeActionGroup.xml
│   │   │   ├── AdminSaveProductsMassAttributesUpdateActionGroup.xml
│   │   │   ├── AdminSearchGridByStringNoClearActionGroup.xml
│   │   │   ├── AdminSelectAttributeSetOnEditProductPageActionGroup.xml
│   │   │   ├── AdminSelectCustomAttributeToExistingProductActionGroup.xml
│   │   │   ├── AdminSelectPermanentRedirectCheckBoxActionGroup.xml
│   │   │   ├── AdminSelectWeightTypeOnProductFormActionGroup.xml
│   │   │   ├── AdminSetBackordersOnProductAdvancedInventoryActionGroup.xml
│   │   │   ├── AdminSetEnableQtyIncrementsActionGroup.xml
│   │   │   ├── AdminSetManageStockConfigActionGroup.xml
│   │   │   ├── AdminSetMaxAllowedQtyForProductActionGroup.xml
│   │   │   ├── AdminSetMinAllowedQtyForProductActionGroup.xml
│   │   │   ├── AdminSetNotifyBelowQtyValueActionGroup.xml
│   │   │   ├── AdminSetPriceForMassUpdateActionGroup.xml
│   │   │   ├── AdminSetProductAsNewDateActionGroup.xml
│   │   │   ├── AdminSetProductAttributeUseInLayeredNavigationOptionActionGroup.xml
│   │   │   ├── AdminSetProductDesignSettingsActionGroup.xml
│   │   │   ├── AdminSetProductDisabledActionGroup.xml
│   │   │   ├── AdminSetQtyIncrementsForProductActionGroup.xml
│   │   │   ├── AdminSetQtyUsesDecimalsConfigActionGroup.xml
│   │   │   ├── AdminSetStockStatusActionGroup.xml
│   │   │   ├── AdminSetStockStatusConfigActionGroup.xml
│   │   │   ├── AdminSetUseInSearchValueForProductAttributeActionGroup.xml
│   │   │   ├── AdminSortProductsGridByActionGroup.xml
│   │   │   ├── AdminStartCreateProductAttributeOnProductPageActionGroup.xml
│   │   │   ├── AdminSubmitAdvancedInventoryFormActionGroup.xml
│   │   │   ├── AdminSubmitCategoriesPopupActionGroup.xml
│   │   │   ├── AdminSwitchProductGiftMessageStatusActionGroup.xml
│   │   │   ├── AdminSwitchScopeForProductAttributeActionGroup.xml
│   │   │   ├── AdminToggleAnchorSwitchActionGroup.xml
│   │   │   ├── AdminToggleProductGridColumnByClickingItsNameActionGroup.xml
│   │   │   ├── AdminUnassignCategoryOnProductAndSaveActionGroup.xml
│   │   │   ├── AdminUnassignProductInWebsiteActionGroup.xml
│   │   │   ├── AdminUncheckPermanentRedirectCheckBoxActionGroup.xml
│   │   │   ├── AdminVerifiesListAndGridModeActionGroup.xml
│   │   │   ├── AssertAdminCategoryIncludedToMenuActionGroup.xml
│   │   │   ├── AssertAdminCategoryIsEnabledActionGroup.xml
│   │   │   ├── AssertAdminCategoryIsInactiveActionGroup.xml
│   │   │   ├── AssertAdminCategoryIsListedInCategoriesTreeActionGroup.xml
│   │   │   ├── AssertAdminCategoryIsNotIncludeInMenuActionGroup.xml
│   │   │   ├── AssertAdminCategoryIsNotListedInCategoriesTreeActionGroup.xml
│   │   │   ├── AssertAdminCategoryLevelByParentCategoryLevelActionGroup.xml
│   │   │   ├── AssertAdminCategoryPageTitleActionGroup.xml
│   │   │   ├── AssertAdminCategorySaveSuccessMessageActionGroup.xml
│   │   │   ├── AssertAdminManageStockOnEditPageActionGroup.xml
│   │   │   ├── AssertAdminNoValidationErrorForPriceFieldOnProductEditPageActionGroup.xml
│   │   │   ├── AssertAdminProductAttributeByCodeOnProductFormActionGroup.xml
│   │   │   ├── AssertAdminProductFormAdvancedPricingAddTierPriceActionGroup.xml
│   │   │   ├── AssertAdminProductFormAdvancedPricingCheckTierPriceActionGroup.xml
│   │   │   ├── AssertAdminProductGridCellActionGroup.xml
│   │   │   ├── AssertAdminProductImageRolesSelectedActionGroup.xml
│   │   │   ├── AssertAdminProductInfoOnEditPageActionGroup.xml
│   │   │   ├── AssertAdminProductIsAssignedToCategoryActionGroup.xml
│   │   │   ├── AssertAdminProductPriceUpdatedOnEditPageActionGroup.xml
│   │   │   ├── AssertAdminProductShortDescriptionOnProductEditFormActionGroup.xml
│   │   │   ├── AssertAdminProductStockStatusActionGroup.xml
│   │   │   ├── AssertAdminValidationErrorAppearedForPriceFieldOnProductEditPageActionGroup.xml
│   │   │   ├── AssertAttributeDeletionErrorMessageActionGroup.xml
│   │   │   ├── AssertDiscountsPercentageOfProductsActionGroup.xml
│   │   │   ├── AssertDontSeeProductDetailsOnStorefrontActionGroup.xml
│   │   │   ├── AssertErrorMessageAfterDeletingWebsiteActionGroup.xml
│   │   │   ├── AssertMetaDescriptionInProductEditFormActionGroup.xml
│   │   │   ├── AssertProductAttributePresenceInCatalogProductGridActionGroup.xml
│   │   │   ├── AssertProductAttributeRemovedSuccessfullyActionGroup.xml
│   │   │   ├── AssertProductDescriptionInProductEditFormActionGroup.xml
│   │   │   ├── AssertProductDetailsOnStorefrontActionGroup.xml
│   │   │   ├── AssertProductImageAdminProductPageActionGroup.xml
│   │   │   ├── AssertProductImageNotInAdminProductPageActionGroup.xml
│   │   │   ├── AssertProductImageNotInStorefrontProductPage2ActionGroup.xml
│   │   │   ├── AssertProductImageNotInStorefrontProductPageActionGroup.xml
│   │   │   ├── AssertProductImageStorefrontProductPage2ActionGroup.xml
│   │   │   ├── AssertProductImageStorefrontProductPageActionGroup.xml
│   │   │   ├── AssertProductInStorefrontCategoryPageActionGroup.xml
│   │   │   ├── AssertProductInStorefrontProductPageActionGroup.xml
│   │   │   ├── AssertProductInfoOnEditPageActionGroup.xml
│   │   │   ├── AssertProductIsAssignedToWebsiteActionGroup.xml
│   │   │   ├── AssertProductIsNotAssignedToWebsiteActionGroup.xml
│   │   │   ├── AssertProductNameAndSkuInStorefrontProductPageActionGroup.xml
│   │   │   ├── AssertProductNameAndSkuInStorefrontProductPageByCustomAttributeUrlKeyActionGroup.xml
│   │   │   ├── AssertProductNameInProductEditFormActionGroup.xml
│   │   │   ├── AssertProductOnAdminGridActionGroup.xml
│   │   │   ├── AssertSeeProductAttributeValidationErrorOnManageLabelsTabActionGroup.xml
│   │   │   ├── AssertSeeProductAttributeValidationErrorOnPropertiesTabActionGroup.xml
│   │   │   ├── AssertSeeProductDetailsOnStorefrontRecentlyViewedWidgetActionGroup.xml
│   │   │   ├── AssertStorefrontAttributeOptionPresentInLayeredNavigationActionGroup.xml
│   │   │   ├── AssertStorefrontAttributeOptionQuantityInLayeredNavigationActionGroup.xml
│   │   │   ├── AssertStorefrontBreadcrubmsAreShownActionGroup.xml
│   │   │   ├── AssertStorefrontCategoryCurrentPageIsNthActionGroup.xml
│   │   │   ├── AssertStorefrontCategorySimpleProductShownActionGroup.xml
│   │   │   ├── AssertStorefrontCustomOptionCheckboxByPriceActionGroup.xml
│   │   │   ├── AssertStorefrontCustomProductAttributeActionGroup.xml
│   │   │   ├── AssertStorefrontLayeredNavigationCategoryAndPriceActionGroup.xml
│   │   │   ├── AssertStorefrontLayeredNavigationCategoryFilterNotVisibleActionGroup.xml
│   │   │   ├── AssertStorefrontLayeredNavigationCategoryFilterVisibleActionGroup.xml
│   │   │   ├── AssertStorefrontNoProductsFoundActionGroup.xml
│   │   │   ├── AssertStorefrontProductAbsentOnCategoryPageActionGroup.xml
│   │   │   ├── AssertStorefrontProductAttributeLabelVisibleActionGroup.xml
│   │   │   ├── AssertStorefrontProductControlsAreNotVisibleWithoutHoverActionGroup.xml
│   │   │   ├── AssertStorefrontProductControlsAreVisibleOnHoverActionGroup.xml
│   │   │   ├── AssertStorefrontProductDescriptionActionGroup.xml
│   │   │   ├── AssertStorefrontProductDetailPageFinalPriceActionGroup.xml
│   │   │   ├── AssertStorefrontProductDetailPageNameActionGroup.xml
│   │   │   ├── AssertStorefrontProductDetailPageNameAndUrlActionGroup.xml
│   │   │   ├── AssertStorefrontProductDetailPageTierPriceActionGroup.xml
│   │   │   ├── AssertStorefrontProductDetailPageTierPriceWithCurrencyActionGroup.xml
│   │   │   ├── AssertStorefrontProductDropDownOptionValueActionGroup.xml
│   │   │   ├── AssertStorefrontProductImageAppearsOnProductPagePreviewActionGroup.xml
│   │   │   ├── AssertStorefrontProductInfoMainProductNameActionGroup.xml
│   │   │   ├── AssertStorefrontProductIsPresentOnCategoryPageActionGroup.xml
│   │   │   ├── AssertStorefrontProductPageGalleryChangingFullscreenImageByRibbonActionGroup.xml
│   │   │   ├── AssertStorefrontProductPageGalleryChangingMainImageByRibbonActionGroup.xml
│   │   │   ├── AssertStorefrontProductPageGalleryFullscreenThumbnailDragActionGroup.xml
│   │   │   ├── AssertStorefrontProductPageGalleryImageDimensionsActionGroup.xml
│   │   │   ├── AssertStorefrontProductPageGalleryImagePositionInThumbnailRibbonActionGroup.xml
│   │   │   ├── AssertStorefrontProductPageGalleryMainImageButtonsActionGroup.xml
│   │   │   ├── AssertStorefrontProductPageGalleryThumbnailDragActionGroup.xml
│   │   │   ├── AssertStorefrontProductPriceInCategoryPageActionGroup.xml
│   │   │   ├── AssertStorefrontProductPricesActionGroup.xml
│   │   │   ├── AssertStorefrontProductSpecialPriceInCategoryPageActionGroup.xml
│   │   │   ├── AssertStorefrontProductStockStatusOnProductPageActionGroup.xml
│   │   │   ├── AssertStorefrontShortProductDescriptionActionGroup.xml
│   │   │   ├── AssertSubTotalOnStorefrontMinicartActionGroup.xml
│   │   │   ├── AssertTextInAdminProductRelatedUpSellCrossSellSectionActionGroup.xml
│   │   │   ├── AssertWebsiteIsAvailableInProductWebsitesActionGroup.xml
│   │   │   ├── AssertWebsiteIsNotAvailableInProductWebsitesActionGroup.xml
│   │   │   ├── CategoryPresentActionGroup.xml
│   │   │   ├── ChangeSeoUrlKeyActionGroup.xml
│   │   │   ├── ChangeSeoUrlKeyForSubCategoryActionGroup.xml
│   │   │   ├── ChangeStatusProductUsingProductGridActionGroup.xml
│   │   │   ├── ChangeUseForPromoRuleConditionsProductAttributeActionGroup.xml
│   │   │   ├── CheckAdminProductGridColumnOptionActionGroup.xml
│   │   │   ├── CheckAttributeInMoreInformationTabActionGroup.xml
│   │   │   ├── CheckAttributeNotInMoreInformationTabActionGroup.xml
│   │   │   ├── CheckCategoryImageInAdminActionGroup.xml
│   │   │   ├── CheckCategoryNameIsRequiredFieldActionGroup.xml
│   │   │   ├── CheckCategoryOnStorefrontActionGroup.xml
│   │   │   ├── CheckCustomizableOptionImportActionGroup.xml
│   │   │   ├── CheckItemInLayeredNavigationActionGroup.xml
│   │   │   ├── CheckProductsOrderActionGroup.xml
│   │   │   ├── CheckRequiredFieldsInProductFormActionGroup.xml
│   │   │   ├── ClearFiltersAdminProductGridActionGroup.xml
│   │   │   ├── ClearProductsFilterActionGroup.xml
│   │   │   ├── ConfirmChangeInputTypeModalActionGroup.xml
│   │   │   ├── CreateAttributeDropdownNthOptionActionGroup.xml
│   │   │   ├── CreateAttributeDropdownNthOptionAsDefaultActionGroup.xml
│   │   │   ├── CreateCategoryActionGroup.xml
│   │   │   ├── CreateCustomAttributeActionGroup.xml
│   │   │   ├── CreateCustomRadioOptionsActionGroup.xml
│   │   │   ├── CreateDefaultAttributeSetActionGroup.xml
│   │   │   ├── CreateNewProductActionGroup.xml
│   │   │   ├── CreateProductAttributeActionGroup.xml
│   │   │   ├── CreateProductAttributeWithDateFieldActionGroup.xml
│   │   │   ├── CreateProductAttributeWithDatetimeFieldActionGroup.xml
│   │   │   ├── CreateProductAttributeWithTextFieldActionGroup.xml
│   │   │   ├── CreateSimpleProductAndAddToWebsiteActionGroup.xml
│   │   │   ├── CreatedProductConnectToWebsiteActionGroup.xml
│   │   │   ├── DeleteAllDuplicateProductUsingProductGridActionGroup.xml
│   │   │   ├── DeleteAllProductsUsingProductGridActionGroup.xml
│   │   │   ├── DeleteAttributeSetByLabelActionGroup.xml
│   │   │   ├── DeleteCategoryActionGroup.xml
│   │   │   ├── DeleteMostRecentCategoryActionGroup.xml
│   │   │   ├── DeleteProductActionGroup.xml
│   │   │   ├── DeleteProductAttributeActionGroup.xml
│   │   │   ├── DeleteProductAttributeByAttributeCodeActionGroup.xml
│   │   │   ├── DeleteProductAttributeByCodeActionGroup.xml
│   │   │   ├── DeleteProductByNameActionGroup.xml
│   │   │   ├── DeleteProductBySkuActionGroup.xml
│   │   │   ├── DeleteProductUsingProductGridActionGroup.xml
│   │   │   ├── DeleteProductsByKeywordActionGroup.xml
│   │   │   ├── DeleteProductsIfTheyExistActionGroup.xml
│   │   │   ├── DisableProductLabelActionGroup.xml
│   │   │   ├── ExpandAdminProductSectionActionGroup.xml
│   │   │   ├── FillAdminSimpleProductFormActionGroup.xml
│   │   │   ├── FillCategoryFormActionGroup.xml
│   │   │   ├── FillCategoryNameAndUrlKeyAndSaveActionGroup.xml
│   │   │   ├── FillMainProductFormActionGroup.xml
│   │   │   ├── FillMainProductFormByStringActionGroup.xml
│   │   │   ├── FillMainProductFormNoWeightActionGroup.xml
│   │   │   ├── FillNewProductCategoryActionGroup.xml
│   │   │   ├── FillProductNameAndSkuInProductFormActionGroup.xml
│   │   │   ├── FilterAndSelectProductActionGroup.xml
│   │   │   ├── FilterProductAttributeByAttributeCodeActionGroup.xml
│   │   │   ├── FilterProductAttributeByAttributeLabelActionGroup.xml
│   │   │   ├── FilterProductAttributeByDefaultLabelActionGroup.xml
│   │   │   ├── FilterProductAttributeSetGridByAttributeSetNameActionGroup.xml
│   │   │   ├── FilterProductGridByCustomDateRangeActionGroup.xml
│   │   │   ├── FilterProductGridByDisabledStatusActionGroup.xml
│   │   │   ├── FilterProductGridByEnabledStatusActionGroup.xml
│   │   │   ├── FilterProductGridByName2ActionGroup.xml
│   │   │   ├── FilterProductGridByNameActionGroup.xml
│   │   │   ├── FilterProductGridByPriceRangeActionGroup.xml
│   │   │   ├── FilterProductGridBySetNewFromDateActionGroup.xml
│   │   │   ├── FilterProductGridBySku2ActionGroup.xml
│   │   │   ├── FilterProductGridBySkuActionGroup.xml
│   │   │   ├── FilterProductGridBySkuAndNameActionGroup.xml
│   │   │   ├── FilterProductInGridByStoreViewAndNameActionGroup.xml
│   │   │   ├── GoToAdminCategoryPageByIdActionGroup.xml
│   │   │   ├── GoToAttributeGridPageActionGroup.xml
│   │   │   ├── GoToAttributeSetByNameActionGroup.xml
│   │   │   ├── GoToCreateCategoryPageActionGroup.xml
│   │   │   ├── GoToCreateProductPageActionGroup.xml
│   │   │   ├── GoToProductCatalogPageActionGroup.xml
│   │   │   ├── GoToSpecifiedCreateProductPageActionGroup.xml
│   │   │   ├── GoToStorefrontCategoryPageByParametersActionGroup.xml
│   │   │   ├── GoToSubCategoryPageActionGroup.xml
│   │   │   ├── ImportProductCustomizableOptionsActionGroup.xml
│   │   │   ├── MoveCategoryActionGroup.xml
│   │   │   ├── NavigateToAndResetProductAttributeGridToDefaultViewActionGroup.xml
│   │   │   ├── NavigateToAndResetProductGridToDefaultViewActionGroup.xml
│   │   │   ├── NavigateToCreatedCategoryActionGroup.xml
│   │   │   ├── NavigateToCreatedProductAttributeActionGroup.xml
│   │   │   ├── NavigateToCreatedProductEditPageActionGroup.xml
│   │   │   ├── NavigateToEditProductAttributeActionGroup.xml
│   │   │   ├── NavigateToMediaGalleryActionGroup.xml
│   │   │   ├── OpenCategoryFromCategoryTreeActionGroup.xml
│   │   │   ├── OpenEditProductOnBackendActionGroup.xml
│   │   │   ├── OpenProductAttributeFromSearchResultInGridActionGroup.xml
│   │   │   ├── OpenProductForEditByClickingRowXColumnYInProductGridActionGroup.xml
│   │   │   ├── OpenProductFromCategoryPageActionGroup.xml
│   │   │   ├── OpenStoreFrontProductPageActionGroup.xml
│   │   │   ├── OpenStorefrontProductPageByProductNameActionGroup.xml
│   │   │   ├── ProductSetAdvancedPricingActionGroup.xml
│   │   │   ├── ProductSetAdvancedPricingWithIndexActionGroup.xml
│   │   │   ├── ProductSetAdvancedTierFixedPricingActionGroup.xml
│   │   │   ├── ProductSetWebsiteActionGroup.xml
│   │   │   ├── RemoveCategoryFromProductActionGroup.xml
│   │   │   ├── RemoveCategoryImageActionGroup.xml
│   │   │   ├── RemoveProductImageActionGroup.xml
│   │   │   ├── RemoveProductImageByNameActionGroup.xml
│   │   │   ├── ResetAdminProductGridColumnsActionGroup.xml
│   │   │   ├── ResetImportOptionFilterActionGroup.xml
│   │   │   ├── ResetProductGridToDefaultViewActionGroup.xml
│   │   │   ├── RestoreLayoutSettingActionGroup.xml
│   │   │   ├── SaveAttributeSetActionGroup.xml
│   │   │   ├── SaveProductAttributeActionGroup.xml
│   │   │   ├── SaveProductAttributeInUseActionGroup.xml
│   │   │   ├── SaveProductFormActionGroup.xml
│   │   │   ├── SaveProductFormNoSuccessCheckActionGroup.xml
│   │   │   ├── SearchAndMultiselectActionGroup.xml
│   │   │   ├── SearchAttributeByCodeOnProductAttributeGridActionGroup.xml
│   │   │   ├── SearchForProductOnBackendActionGroup.xml
│   │   │   ├── SearchForProductOnBackendByNameActionGroup.xml
│   │   │   ├── SearchProductGridByKeyword2ActionGroup.xml
│   │   │   ├── SearchProductGridByKeywordActionGroup.xml
│   │   │   ├── SelectProductInWebsitesActionGroup.xml
│   │   │   ├── SetCategoryByNameActionGroup.xml
│   │   │   ├── SetProductUrlKeyActionGroup.xml
│   │   │   ├── SetProductUrlKeyByStringActionGroup.xml
│   │   │   ├── SortProductsByIdAscendingActionGroup.xml
│   │   │   ├── SortProductsByIdDescendingActionGroup.xml
│   │   │   ├── StorefrontAddCategoryProductToCompareActionGroup.xml
│   │   │   ├── StorefrontAddMultipleSimpleProductToBundleProductActionGroup.xml
│   │   │   ├── StorefrontAddProductReviewActionGroup.xml
│   │   │   ├── StorefrontAddProductToCartWithQtyActionGroup.xml
│   │   │   ├── StorefrontAddProductToCompareActionGroup.xml
│   │   │   ├── StorefrontAddSimpleProductWithQtyActionGroup.xml
│   │   │   ├── StorefrontAddToCartCustomOptionsProductPageActionGroup.xml
│   │   │   ├── StorefrontAssertActiveProductImageActionGroup.xml
│   │   │   ├── StorefrontAssertCategoryNameIsNotShownInMenuActionGroup.xml
│   │   │   ├── StorefrontAssertCategoryNameIsShownInMenuActionGroup.xml
│   │   │   ├── StorefrontAssertCustomOptionByTitleActionGroup.xml
│   │   │   ├── StorefrontAssertFotoramaImageAvailabilityActionGroup.xml
│   │   │   ├── StorefrontAssertGiftMessageFieldsActionGroup.xml
│   │   │   ├── StorefrontAssertNotExistProductInRecentlyComparedWidgetActionGroup.xml
│   │   │   ├── StorefrontAssertPageNotFoundErrorOnProductDetailPageActionGroup.xml
│   │   │   ├── StorefrontAssertProductImagesOnProductPageActionGroup.xml
│   │   │   ├── StorefrontAssertProductInRecentlyComparedWidgetActionGroup.xml
│   │   │   ├── StorefrontAssertProductInRecentlyOrderedWidgetActionGroup.xml
│   │   │   ├── StorefrontAssertProductInWidgetActionGroup.xml
│   │   │   ├── StorefrontAssertProductNameIsNotOnProductMainPageActionGroup.xml
│   │   │   ├── StorefrontAssertProductNameIsNotShownOnProductPageActionGroup.xml
│   │   │   ├── StorefrontAssertProductNameOnProductMainPageActionGroup.xml
│   │   │   ├── StorefrontAssertProductNameOnProductPageActionGroup.xml
│   │   │   ├── StorefrontAssertProductPageAddToWishlistButtonIsNotPresentActionGroup.xml
│   │   │   ├── StorefrontAssertProductPriceOnCategoryPageActionGroup.xml
│   │   │   ├── StorefrontAssertProductPriceOnProductPageActionGroup.xml
│   │   │   ├── StorefrontAssertProductSkuOnProductPageActionGroup.xml
│   │   │   ├── StorefrontAssertProductSpecialPriceOnProductPageActionGroup.xml
│   │   │   ├── StorefrontAssertProperUrlIsShownActionGroup.xml
│   │   │   ├── StorefrontAssertRelatedProductOnProductPageActionGroup.xml
│   │   │   ├── StorefrontAssertSubCategoryNameIsNotShownInMenuActionGroup.xml
│   │   │   ├── StorefrontAssertUpSellProductOnProductPageActionGroup.xml
│   │   │   ├── StorefrontCategoryPageSortAscendingActionGroup.xml
│   │   │   ├── StorefrontCategoryPageSortDescendingActionGroup.xml
│   │   │   ├── StorefrontCategoryPageSortProductActionGroup.xml
│   │   │   ├── StorefrontCheckAddToCartButtonAbsenceActionGroup.xml
│   │   │   ├── StorefrontCheckCategoryActionGroup.xml
│   │   │   ├── StorefrontCheckCategorySimpleProductActionGroup.xml
│   │   │   ├── StorefrontCheckCompareSidebarProductActionGroup.xml
│   │   │   ├── StorefrontCheckCompareSimpleProductActionGroup.xml
│   │   │   ├── StorefrontCheckPresentSubCategoryActionGroup.xml
│   │   │   ├── StorefrontCheckProductIsMissingInCategoryProductsPageActionGroup.xml
│   │   │   ├── StorefrontCheckProductPositionActionGroup.xml
│   │   │   ├── StorefrontCheckProductPriceInCategoryActionGroup.xml
│   │   │   ├── StorefrontCheckSimpleProductActionGroup.xml
│   │   │   ├── StorefrontClearCompareActionGroup.xml
│   │   │   ├── StorefrontClickAddToCartButtonActionGroup.xml
│   │   │   ├── StorefrontClickAddToCartOnProductPageActionGroup.xml
│   │   │   ├── StorefrontClickOnProductFromSidebarCompareListActionGroup.xml
│   │   │   ├── StorefrontDontSeeNoProductsFoundActionGroup.xml
│   │   │   ├── StorefrontGoToCategoryPageActionGroup.xml
│   │   │   ├── StorefrontGoToSubCategoryPageActionGroup.xml
│   │   │   ├── StorefrontGoToSubSubCategoryPageActionGroup.xml
│   │   │   ├── StorefrontHoverProductOnCategoryPageActionGroup.xml
│   │   │   ├── StorefrontNavigateCategoryNextPageActionGroup.xml
│   │   │   ├── StorefrontNavigateCategoryPageActionGroup.xml
│   │   │   ├── StorefrontNavigateToCategoryUrlActionGroup.xml
│   │   │   ├── StorefrontOpenAndCheckComparisionActionGroup.xml
│   │   │   ├── StorefrontOpenHomePageActionGroup.xml
│   │   │   ├── StorefrontOpenProductEntityPageActionGroup.xml
│   │   │   ├── StorefrontOpenProductFromCategoryPageActionGroup.xml
│   │   │   ├── StorefrontOpenProductPageActionGroup.xml
│   │   │   ├── StorefrontOpenProductPageOnSecondStoreActionGroup.xml
│   │   │   ├── StorefrontOpenProductPageUsingStoreCodeInUrlActionGroup.xml
│   │   │   ├── StorefrontProductPageCloseFullscreenGalleryActionGroup.xml
│   │   │   ├── StorefrontProductPageGalleryDragMainImageBackActionGroup.xml
│   │   │   ├── StorefrontProductPageGalleryDragMainImageForwardActionGroup.xml
│   │   │   ├── StorefrontProductPageOpenImageFullscreenActionGroup.xml
│   │   │   ├── StorefrontProductPageSelectDropDownOptionValueActionGroup.xml
│   │   │   ├── StorefrontProductPageSelectRadioButtonOptionValueActionGroup.xml
│   │   │   ├── StorefrontRemoveFirstProductFromCompareActionGroup.xml
│   │   │   ├── StorefrontSelectCustomOptionDropDownAndAssertPricesActionGroup.xml
│   │   │   ├── StorefrontSelectCustomOptionRadioAndAssertPricesActionGroup.xml
│   │   │   ├── StorefrontSwitchCategoryViewToGridModeActionGroup.xml
│   │   │   ├── StorefrontSwitchCategoryViewToListModeActionGroup.xml
│   │   │   ├── StorefrontSwitchStoreActionGroup.xml
│   │   │   ├── SwitchCategoryStoreViewActionGroup.xml
│   │   │   ├── SwitchCategoryToAllStoreViewActionGroup.xml
│   │   │   ├── SwitchCategoryWebSiteStoreViewActionGroup.xml
│   │   │   ├── SwitchToTheNewStoreViewActionGroup.xml
│   │   │   ├── TestDynamicValidationHintActionGroup.xml
│   │   │   ├── ToggleAdminProductGridColumnsDropdownActionGroup.xml
│   │   │   ├── ToggleProductEnabledActionGroup.xml
│   │   │   ├── UnassignAttributeFromGroupActionGroup.xml
│   │   │   ├── UnassignWebsiteFromProductActionGroup.xml
│   │   │   ├── UpdateAllIndexerByScheduleActionGroup.xml
│   │   │   ├── VerifyCategoryPageParametersActionGroup.xml
│   │   │   ├── VerifyProductTypeOrderActionGroup.xml
│   │   │   ├── VerifySuccessMessagesWithoutWarningActionGroup.xml
│   │   │   └── ViewProductInAdminGridActionGroup.xml
│   │   ├── Data
│   │   │   ├── AdminMenuData.xml
│   │   │   ├── AdminProductAttributeMessageData.xml
│   │   │   ├── AttributeSetData.xml
│   │   │   ├── CatalogAttributeGroupData.xml
│   │   │   ├── CatalogAttributeSetData.xml
│   │   │   ├── CatalogConfigurationData.xml
│   │   │   ├── CatalogInventoryConfigData.xml
│   │   │   ├── CatalogPriceConfigData.xml
│   │   │   ├── CatalogPriceData.xml
│   │   │   ├── CatalogRecentlyProductsConfigData.xml
│   │   │   ├── CatalogSpecialPriceData.xml
│   │   │   ├── CatalogStorefrontConfigData.xml
│   │   │   ├── CategoryData.xml
│   │   │   ├── ConfigData.xml
│   │   │   ├── ConstData.xml
│   │   │   ├── CustomAttributeData.xml
│   │   │   ├── FrontendLabelData.xml
│   │   │   ├── GroupPriceData.xml
│   │   │   ├── ImageContentData.xml
│   │   │   ├── ImageData.xml
│   │   │   ├── NonexistentProductData.xml
│   │   │   ├── ProductAttributeData.xml
│   │   │   ├── ProductAttributeMassUpdateData.xml
│   │   │   ├── ProductAttributeMediaGalleryEntryData.xml
│   │   │   ├── ProductAttributeOptionData.xml
│   │   │   ├── ProductAttributeSetData.xml
│   │   │   ├── ProductData.xml
│   │   │   ├── ProductDesignData.xml
│   │   │   ├── ProductExtensionAttributeData.xml
│   │   │   ├── ProductFormData.xml
│   │   │   ├── ProductGridData.xml
│   │   │   ├── ProductLinkData.xml
│   │   │   ├── ProductLinksData.xml
│   │   │   ├── ProductOptionData.xml
│   │   │   ├── ProductOptionValueData.xml
│   │   │   ├── QueueConsumerData.xml
│   │   │   ├── RecentlyViewedProductStoreData.xml
│   │   │   ├── SeoConfigData.xml
│   │   │   ├── SimpleProductOptionData.xml
│   │   │   ├── StockItemData.xml
│   │   │   ├── StoreLabelData.xml
│   │   │   ├── TierPriceData.xml
│   │   │   ├── VirtualProductOptionData.xml
│   │   │   └── WidgetsData.xml
│   │   ├── Helper
│   │   │   ├── CatalogHelper.php
│   │   │   └── LocalFileAssertions.php
│   │   ├── LICENSE.txt
│   │   ├── LICENSE_AFL.txt
│   │   ├── Metadata
│   │   │   ├── CatalogAttributeSetMeta.xml
│   │   │   ├── CatalogConfigurationMeta.xml
│   │   │   ├── CatalogPriceMeta.xml
│   │   │   ├── CatalogRecentlyProductsMeta.xml
│   │   │   ├── CatalogSpecialPriceMeta.xml
│   │   │   ├── CatalogTierPriceMeta.xml
│   │   │   ├── CategoryMeta.xml
│   │   │   ├── CustomAttributeMeta.xml
│   │   │   ├── EmptyExtensionAttributeMeta.xml
│   │   │   ├── FrontendLabelMeta.xml
│   │   │   ├── ImageContentMeta.xml
│   │   │   ├── ProductAttributeMediaGalleryEntryMeta.xml
│   │   │   ├── ProductAttributeMeta.xml
│   │   │   ├── ProductAttributeOptionMeta.xml
│   │   │   ├── ProductAttributeSetMeta.xml
│   │   │   ├── ProductExtensionAttributeMeta.xml
│   │   │   ├── ProductLinkExtensionAttributeMeta.xml
│   │   │   ├── ProductLinkMeta.xml
│   │   │   ├── ProductLinksMeta.xml
│   │   │   ├── ProductMeta.xml
│   │   │   ├── ProductOptionMeta.xml
│   │   │   ├── ProductOptionValueMeta.xml
│   │   │   ├── StockItemMeta.xml
│   │   │   ├── StoreLabelMeta.xml
│   │   │   └── ValidationRuleMeta.xml
│   │   ├── Page
│   │   │   ├── AdminCategoryEditPage.xml
│   │   │   ├── AdminCategoryPage.xml
│   │   │   ├── AdminNewWidgetPage.xml
│   │   │   ├── AdminProductAttributeFormPage.xml
│   │   │   ├── AdminProductAttributeGridPage.xml
│   │   │   ├── AdminProductAttributeSetEditPage.xml
│   │   │   ├── AdminProductAttributeSetGridPage.xml
│   │   │   ├── AdminProductAttributesEditPage.xml
│   │   │   ├── AdminProductCreatePage.xml
│   │   │   ├── AdminProductDeletePage.xml
│   │   │   ├── AdminProductEditPage.xml
│   │   │   ├── AdminProductIndexPage.xml
│   │   │   ├── ProductCatalogPage.xml
│   │   │   ├── StorefrontCategoryPage.xml
│   │   │   ├── StorefrontProductComparePage.xml
│   │   │   ├── StorefrontProductPage.xml
│   │   │   └── StorefrontStoreViewProductPage.xml
│   │   ├── README.md
│   │   ├── Section
│   │   │   ├── AdminAddProductsToOptionPanelSection.xml
│   │   │   ├── AdminCatalogProductWidgetSection.xml
│   │   │   ├── AdminCatalogStorefrontConfigSection.xml
│   │   │   ├── AdminCategoryBasicFieldSection
│   │   │   │   ├── AdminCategoryBasicFieldSection.xml
│   │   │   │   ├── CategoryContentSection.xml
│   │   │   │   ├── CategoryDesignSection.xml
│   │   │   │   └── CategoryDisplaySettingsSection.xml
│   │   │   ├── AdminCategoryContentSection.xml
│   │   │   ├── AdminCategoryDisplaySettingsSection.xml
│   │   │   ├── AdminCategoryMainActionsSection.xml
│   │   │   ├── AdminCategoryMessagesSection.xml
│   │   │   ├── AdminCategoryModalSection.xml
│   │   │   ├── AdminCategoryProductsGridSection.xml
│   │   │   ├── AdminCategoryProductsSection.xml
│   │   │   ├── AdminCategorySEOSection.xml
│   │   │   ├── AdminCategoryScheduleDesignUpdateSection.xml
│   │   │   ├── AdminCategorySidebarActionSection.xml
│   │   │   ├── AdminCategorySidebarTreeSection.xml
│   │   │   ├── AdminCategoryWarningMessagesPopupSection.xml
│   │   │   ├── AdminChecksListAndGridModeSection.xml
│   │   │   ├── AdminCreateNewProductAttributeSection.xml
│   │   │   ├── AdminCreateProductAttributeSection
│   │   │   │   ├── AdvancedAttributePropertiesSection.xml
│   │   │   │   ├── AttributeDeleteModalSection.xml
│   │   │   │   ├── AttributeManageSwatchSection.xml
│   │   │   │   ├── AttributeOptionsSection.xml
│   │   │   │   ├── AttributePropertiesSection.xml
│   │   │   │   └── StorefrontPropertiesSection.xml
│   │   │   ├── AdminEditProductAttributesSection.xml
│   │   │   ├── AdminNewWidgetSection.xml
│   │   │   ├── AdminNewWidgetSelectProductPopupSection.xml
│   │   │   ├── AdminProductAddAttributeModalSection.xml
│   │   │   ├── AdminProductAttributeGridSection.xml
│   │   │   ├── AdminProductAttributeManageLabelsSection.xml
│   │   │   ├── AdminProductAttributeOptionsSection.xml
│   │   │   ├── AdminProductAttributeSetActionSection.xml
│   │   │   ├── AdminProductAttributeSetEditSection.xml
│   │   │   ├── AdminProductAttributeSetGridSection.xml
│   │   │   ├── AdminProductAttributeSetSection
│   │   │   │   ├── AdminProductAttributeSetSection.xml
│   │   │   │   ├── AttributeSetSection.xml
│   │   │   │   ├── GroupSection.xml
│   │   │   │   ├── ModifyAttributesSection.xml
│   │   │   │   └── UnassignedAttributesSection.xml
│   │   │   ├── AdminProductAttributesSection.xml
│   │   │   ├── AdminProductCategoryCreationSection.xml
│   │   │   ├── AdminProductContentSection.xml
│   │   │   ├── AdminProductCrossSellModalSection.xml
│   │   │   ├── AdminProductCustomOptionsPaginationSection.xml
│   │   │   ├── AdminProductCustomizableOptionsSection
│   │   │   │   ├── AdminProductCustomizableOptionsSection.xml
│   │   │   │   └── AdminProductImportOptionsSection.xml
│   │   │   ├── AdminProductDropdownOrderSection.xml
│   │   │   ├── AdminProductFiltersSection.xml
│   │   │   ├── AdminProductFormActionSection.xml
│   │   │   ├── AdminProductFormAdvancedPricingSection.xml
│   │   │   ├── AdminProductFormAttributeSection
│   │   │   │   ├── AdminProductFormAttributeSection.xml
│   │   │   │   ├── AdminProductFormNewAttributeAdvancedSection.xml
│   │   │   │   ├── AdminProductFormNewAttributeNewSetSection.xml
│   │   │   │   ├── AdminProductFormNewAttributeSection.xml
│   │   │   │   └── AdminProductFormNewAttributeStorefrontSection.xml
│   │   │   ├── AdminProductFormChangeStoreSection.xml
│   │   │   ├── AdminProductFormSection
│   │   │   │   ├── AdminAddRelatedProductsModalSection.xml
│   │   │   │   ├── AdminProductAttributeSection.xml
│   │   │   │   ├── AdminProductFormAdvancedPricingSection.xml
│   │   │   │   ├── AdminProductFormCostPricingSection.xml
│   │   │   │   ├── AdminProductFormRelatedUpSellCrossSellSection.xml
│   │   │   │   ├── AdminProductFormSection.xml
│   │   │   │   ├── ProductDescriptionWysiwygSection.xml
│   │   │   │   ├── ProductDesignSection.xml
│   │   │   │   ├── ProductInWebsitesSection.xml
│   │   │   │   └── ProductShortDescriptionWysiwygSection.xml
│   │   │   ├── AdminProductGiftOptionsSection.xml
│   │   │   ├── AdminProductGridActionSection.xml
│   │   │   ├── AdminProductGridConfirmActionSection.xml
│   │   │   ├── AdminProductGridFilterSection.xml
│   │   │   ├── AdminProductGridPaginationSection.xml
│   │   │   ├── AdminProductGridSection.xml
│   │   │   ├── AdminProductGridTableHeaderSection.xml
│   │   │   ├── AdminProductImagePlaceholderConfigSection.xml
│   │   │   ├── AdminProductImagesSection.xml
│   │   │   ├── AdminProductMessagesSection.xml
│   │   │   ├── AdminProductModalSlideGridSection.xml
│   │   │   ├── AdminProductMultiselectAttributeSection.xml
│   │   │   ├── AdminProductRelatedUpSellCrossSellSection
│   │   │   │   ├── AdminAddUpSellProductsModalSection.xml
│   │   │   │   └── AdminProductFormRelatedUpSellCrossSellSection.xml
│   │   │   ├── AdminProductSEOSection.xml
│   │   │   ├── AdminUpdateAttributesSection
│   │   │   │   ├── AdminUpdateAttributesAdvancedInventorySection.xml
│   │   │   │   ├── AdminUpdateAttributesSection.xml
│   │   │   │   └── AdminUpdateAttributesWebsiteSection.xml
│   │   │   ├── CatalogSubmenuSection.xml
│   │   │   ├── NewProductPageSection.xml
│   │   │   ├── ProductsPageSection.xml
│   │   │   ├── StoreFrontRecentProductSection.xml
│   │   │   ├── StorefrontCategoryBottomToolbarSection.xml
│   │   │   ├── StorefrontCategoryFilterSection.xml
│   │   │   ├── StorefrontCategoryMainSection.xml
│   │   │   ├── StorefrontCategoryProductSection.xml
│   │   │   ├── StorefrontCategorySidebarSection
│   │   │   │   ├── StorefrontCategorySidebarMobileSection.xml
│   │   │   │   └── StorefrontCategorySidebarSection.xml
│   │   │   ├── StorefrontCategoryTopToolbarSection.xml
│   │   │   ├── StorefrontComparisonSidebarSection.xml
│   │   │   ├── StorefrontFooterSection.xml
│   │   │   ├── StorefrontHeaderSection.xml
│   │   │   ├── StorefrontNavigationSection.xml
│   │   │   ├── StorefrontProducRelatedProductsSection.xml
│   │   │   ├── StorefrontProductActionSection.xml
│   │   │   ├── StorefrontProductCompareMainSection.xml
│   │   │   ├── StorefrontProductInfoDetailsSection.xml
│   │   │   ├── StorefrontProductInfoMainSection.xml
│   │   │   ├── StorefrontProductMediaSection.xml
│   │   │   ├── StorefrontProductMoreInformationSection.xml
│   │   │   ├── StorefrontProductPageDesignSection.xml
│   │   │   ├── StorefrontProductPageSection.xml
│   │   │   ├── StorefrontProductReviewsSection.xml
│   │   │   ├── StorefrontProductUpSellProductsSection.xml
│   │   │   └── StorefrontWidgetsSection.xml
│   │   ├── Test
│   │   │   ├── AddExistingProductAttributeFromProductPageTest.xml
│   │   │   ├── AddNewProductAttributeInProductPageTest.xml
│   │   │   ├── AddOutOfStockProductToCompareListTest.xml
│   │   │   ├── AddProductToCartWithMinimumQuantity.xml
│   │   │   ├── AddToCartCrossSellTest.xml
│   │   │   ├── AdminAddAndUpdateCustomGroupInAttributeSetTest.xml
│   │   │   ├── AdminAddDefaultImageSimpleProductTest.xml
│   │   │   ├── AdminAddDefaultImageVirtualProductTest.xml
│   │   │   ├── AdminAddImageForCategoryTest.xml
│   │   │   ├── AdminAddImageToWYSIWYGCatalogTest.xml
│   │   │   ├── AdminAddImageToWYSIWYGProductTest.xml
│   │   │   ├── AdminAddInStockProductToTheCartTest.xml
│   │   │   ├── AdminAlertDoseNotAppearOnProductPageTest.xml
│   │   │   ├── AdminApplyCatalogStorefrontConfigurationSettingsTest.xml
│   │   │   ├── AdminApplyChangePriceForConfigurableProductWithAssignedSimpleProductsTest.xml
│   │   │   ├── AdminApplyTierPriceToProductTest
│   │   │   │   ├── AdminApplyTierPriceToProductTest.xml
│   │   │   │   ├── AdminApplyTierPriceToProductWithPercentageDiscountTest.xml
│   │   │   │   └── StoreFrontDeleteProductImagesAssignedDifferentRolesTest.xml
│   │   │   ├── AdminAssignProductAttributeToAttributeSetTest.xml
│   │   │   ├── AdminBackorderAllowedAddProductToCartTest.xml
│   │   │   ├── AdminCatalogCategoriesNavigateMenuTest.xml
│   │   │   ├── AdminCatalogProductsNavigateMenuTest.xml
│   │   │   ├── AdminChangeArrangementOfAttributesInAnAttributeSetTest.xml
│   │   │   ├── AdminChangeCategoryDisplaySettingsOnStorefrontTest.xml
│   │   │   ├── AdminChangeProductAttributeGroupTest.xml
│   │   │   ├── AdminChangeProductAttributeSetTest.xml
│   │   │   ├── AdminCheckConfigurableProductPriceWhenChildProductPriceUpdatedTest.xml
│   │   │   ├── AdminCheckConfigurableProductPriceWithDisabledChildProductTest.xml
│   │   │   ├── AdminCheckConfigurableProductPriceWithOutOfStockChildProductTest.xml
│   │   │   ├── AdminCheckCustomAttributeValuesAfterProductSaveTest.xml
│   │   │   ├── AdminCheckInactiveAndNotIncludeInMenuCategoryAndSubcategoryIsNotVisibleInNavigationTest.xml
│   │   │   ├── AdminCheckInactiveCategoryAndSubcategoryIsNotVisibleInNavigationMenuTest.xml
│   │   │   ├── AdminCheckInactiveIncludeInMenuCategoryAndSubcategoryIsNotVisibleInNavigationTest.xml
│   │   │   ├── AdminCheckMediaRolesForFirstAddedImageViaApiTest.xml
│   │   │   ├── AdminCheckNewCategoryLevelAddedViaApiTest.xml
│   │   │   ├── AdminCheckOutOfStockProductIsNotVisibleInCategoryTest.xml
│   │   │   ├── AdminCheckOutOfStockProductIsVisibleInCategoryTest.xml
│   │   │   ├── AdminCheckPaginationInStorefrontTest.xml
│   │   │   ├── AdminCheckProductListPriceAttributesTest.xml
│   │   │   ├── AdminCheckProductListPriceAttributesWithDifferentCurrencyTest.xml
│   │   │   ├── AdminCheckSubCategoryIsNotVisibleInNavigationMenuTest.xml
│   │   │   ├── AdminChecksIfOnlyOneQuantityConfigurationIsDisplayedForBundleProductWhileCreatingAnOrderTest.xml
│   │   │   ├── AdminCloneProductWithDuplicateUrlTest.xml
│   │   │   ├── AdminConfigureProductImagePlaceholderTest.xml
│   │   │   ├── AdminCreateAndEditSimpleProductSettingsTest.xml
│   │   │   ├── AdminCreateAndEditVirtualProductSettingsTest.xml
│   │   │   ├── AdminCreateAndSwitchProductType
│   │   │   │   ├── AdminCreateSimpleProductSwitchToVirtualTest.xml
│   │   │   │   └── AdminCreateVirtualProductSwitchToSimpleTest.xml
│   │   │   ├── AdminCreateAttributeSetEntityTest.xml
│   │   │   ├── AdminCreateCategoriesWithTheSameCategoryNamesTest.xml
│   │   │   ├── AdminCreateCategoryFromProductPageTest.xml
│   │   │   ├── AdminCreateCategoryTest
│   │   │   │   ├── AdminCategoryFormDisplaySettingsUIValidationTest.xml
│   │   │   │   ├── AdminConfigDefaultCategoryLayoutFromConfigurationSettingTest.xml
│   │   │   │   ├── AdminCreateCategoryTest.xml
│   │   │   │   └── AdminUploadCategoryImageTest.xml
│   │   │   ├── AdminCreateCategoryWithAPIForMultiStoresTest.xml
│   │   │   ├── AdminCreateCategoryWithAnchorFieldTest.xml
│   │   │   ├── AdminCreateCategoryWithCustomRootCategoryTest.xml
│   │   │   ├── AdminCreateCategoryWithFiveNestingTest.xml
│   │   │   ├── AdminCreateCategoryWithInactiveCategoryTest.xml
│   │   │   ├── AdminCreateCategoryWithInactiveIncludeInMenuTest.xml
│   │   │   ├── AdminCreateCategoryWithNoAnchorFieldTest.xml
│   │   │   ├── AdminCreateCategoryWithProductsGridFilterTest.xml
│   │   │   ├── AdminCreateCategoryWithRequiredFieldsTest.xml
│   │   │   ├── AdminCreateCustomProductAttributeWithDropdownFieldTest.xml
│   │   │   ├── AdminCreateDatetimeProductAttributeTest.xml
│   │   │   ├── AdminCreateDropdownProductAttributeTest.xml
│   │   │   ├── AdminCreateDropdownProductAttributeVisibleInStorefrontAdvancedSearchFormTest.xml
│   │   │   ├── AdminCreateDuplicateCategoryTest.xml
│   │   │   ├── AdminCreateDuplicateProductTest.xml
│   │   │   ├── AdminCreateInactiveFlatCategoryAndUpdateAsInactiveTest.xml
│   │   │   ├── AdminCreateInactiveFlatCategoryTest.xml
│   │   │   ├── AdminCreateInactiveInMenuFlatCategoryTest.xml
│   │   │   ├── AdminCreateMultipleSelectProductAttributeVisibleInStorefrontAdvancedSearchFormTest.xml
│   │   │   ├── AdminCreateNewAttributeFromProductPageTest.xml
│   │   │   ├── AdminCreateNewAttributeFromProductTest.xml
│   │   │   ├── AdminCreateNewGroupForAttributeSetTest.xml
│   │   │   ├── AdminCreateProductAttributeFromProductPageTest.xml
│   │   │   ├── AdminCreateProductAttributeRequiredTextFieldTest.xml
│   │   │   ├── AdminCreateProductAttributeTextSwatchFromProductPageTest.xml
│   │   │   ├── AdminCreateProductAttributeVisualSwatchFromProductPageTest.xml
│   │   │   ├── AdminCreateProductCustomAttributeSetTest.xml
│   │   │   ├── AdminCreateProductDuplicateUrlkeyTest
│   │   │   │   ├── AdminCreateProductDuplicateProductTest.xml
│   │   │   │   └── AdminCreateProductDuplicateUrlkeyTest.xml
│   │   │   ├── AdminCreateRootCategoryAndSubcategoriesTest.xml
│   │   │   ├── AdminCreateRootCategoryRequiredFieldsTest.xml
│   │   │   ├── AdminCreateSimpleProductNotVisibleIndividuallyTest.xml
│   │   │   ├── AdminCreateSimpleProductTest
│   │   │   │   ├── AdminConfigDefaultProductLayoutFromConfigurationSettingTest.xml
│   │   │   │   ├── AdminCreateSimpleProductCommaSeparatedPriceTest.xml
│   │   │   │   ├── AdminCreateSimpleProductEmptySKUTest.xml
│   │   │   │   ├── AdminCreateSimpleProductNegativePriceTest.xml
│   │   │   │   ├── AdminCreateSimpleProductTest.xml
│   │   │   │   ├── AdminCreateSimpleProductUrlKeyTest.xml
│   │   │   │   ├── AdminCreateSimpleProductZeroPriceTest.xml
│   │   │   │   └── AdminCreateTwoSimpleProductTest.xml
│   │   │   ├── AdminCreateSimpleProductWithCountryOfManufactureAttributeSKUMaskTest.xml
│   │   │   ├── AdminCreateSimpleProductWithDatetimeAttributeTest.xml
│   │   │   ├── AdminCreateSimpleProductWithUnicodeTest.xml
│   │   │   ├── AdminCreateSubcategoryWithEmptyRequiredFieldsTest.xml
│   │   │   ├── AdminCreateSwatchAttributeWithSpecialCharactersTest.xml
│   │   │   ├── AdminCreateTextEditorProductAttributeTest.xml
│   │   │   ├── AdminCreateVirtualProductFillingRequiredFieldsOnlyTest.xml
│   │   │   ├── AdminCreateVirtualProductOutOfStockWithTierPriceTest.xml
│   │   │   ├── AdminCreateVirtualProductWithCustomOptionsSuiteAndImportOptionsTest.xml
│   │   │   ├── AdminCreateVirtualProductWithTierPriceForGeneralGroupTest.xml
│   │   │   ├── AdminCreateVirtualProductWithTierPriceTest.xml
│   │   │   ├── AdminCreateVirtualProductWithoutManageStockTest.xml
│   │   │   ├── AdminDeleteAttributeSetTest.xml
│   │   │   ├── AdminDeleteConfigurableChildProductsTest.xml
│   │   │   ├── AdminDeleteCustomGroupInAnAttributeSetTest.xml
│   │   │   ├── AdminDeleteDropdownProductAttributeFromAttributeSetTest.xml
│   │   │   ├── AdminDeleteProductAttributeTest.xml
│   │   │   ├── AdminDeleteProductWithCustomOptionTest.xml
│   │   │   ├── AdminDeleteProductsImageInCaseOfMultipleStoresTest.xml
│   │   │   ├── AdminDeleteProductsImageWithCustomOptionTest.xml
│   │   │   ├── AdminDeleteRootCategoryAssignedToStoreTest.xml
│   │   │   ├── AdminDeleteRootCategoryTest.xml
│   │   │   ├── AdminDeleteRootSubCategoryTest.xml
│   │   │   ├── AdminDeleteSimpleProductTest.xml
│   │   │   ├── AdminDeleteSystemProductAttributeTest.xml
│   │   │   ├── AdminDeleteTextFieldProductAttributeFromAttributeSetTest.xml
│   │   │   ├── AdminDeleteVirtualProductTest.xml
│   │   │   ├── AdminDeletedCategoryNotShownAsAvailableOnProductPageTest.xml
│   │   │   ├── AdminDisableProductOnChangingAttributeSetTest.xml
│   │   │   ├── AdminEditTextEditorProductAttributeTest.xml
│   │   │   ├── AdminFilterByNameByStoreViewOnProductGridTest.xml
│   │   │   ├── AdminFilteringCategoryProductsUsingScopeSelectorTest.xml
│   │   │   ├── AdminGridPageNumberAfterSaveAndCloseActionTest.xml
│   │   │   ├── AdminGridPageNumberSetsToOneAfterNewSearchTest.xml
│   │   │   ├── AdminImportCustomizableOptionToProductWithSKUTest.xml
│   │   │   ├── AdminLimitNumberOfProductsInGridTest.xml
│   │   │   ├── AdminMassChangeProductsStatusTest.xml
│   │   │   ├── AdminMassProductAttributeUpdateAddedToQueueTest.xml
│   │   │   ├── AdminMassProductPriceUpdateTest.xml
│   │   │   ├── AdminMassUpdateProductAttributeDatetimeTest.xml
│   │   │   ├── AdminMassUpdateProductAttributesGlobalScopeTest.xml
│   │   │   ├── AdminMassUpdateProductAttributesMissingRequiredFieldTest.xml
│   │   │   ├── AdminMassUpdateProductAttributesStoreViewScopeTest
│   │   │   │   └── AdminMassUpdateProductAttributesStoreViewScopeTest.xml
│   │   │   ├── AdminMassUpdateProductQtyIncrementsTest.xml
│   │   │   ├── AdminMassUpdateProductStatusStoreViewScopeTest
│   │   │   │   └── AdminMassUpdateProductStatusStoreViewScopeTest.xml
│   │   │   ├── AdminMoveAnchoredCategoryTest.xml
│   │   │   ├── AdminMoveAnchoredCategoryToDefaultCategoryTest.xml
│   │   │   ├── AdminMoveCategoryAndCheckUrlRewritesTest.xml
│   │   │   ├── AdminMoveCategoryFromParentAnchoredCategoryTest.xml
│   │   │   ├── AdminMoveCategoryToAnotherPositionInCategoryTreeTest.xml
│   │   │   ├── AdminMoveProductBetweenCategoriesTest.xml
│   │   │   ├── AdminMultipleWebsitesUseDefaultValuesTest.xml
│   │   │   ├── AdminNavigateMultipleUpSellProductsTest.xml
│   │   │   ├── AdminProductAttributeLabelDontAllowHtmlTagsTest.xml
│   │   │   ├── AdminProductCategoryIndexerInUpdateOnScheduleModeTest.xml
│   │   │   ├── AdminProductCustomURLKeyPreservedWhenAssignedToCategoryWithoutCustomURLKeyTest.xml
│   │   │   ├── AdminProductGridCustomViewColumnDisplayTest.xml
│   │   │   ├── AdminProductGridFilteringByCustomAttributeTest.xml
│   │   │   ├── AdminProductGridFilteringByDateAttributeTest.xml
│   │   │   ├── AdminProductGridFilteringByDateWithCustomLocaleTest.xml
│   │   │   ├── AdminProductGridSwitchViewBookmarkTest.xml
│   │   │   ├── AdminProductGridUrlFilterApplierTest.xml
│   │   │   ├── AdminProductImageAssignmentForMultipleStoresTest.xml
│   │   │   ├── AdminProductStatusAttributeDisabledByDefaultTest.xml
│   │   │   ├── AdminProductTypeSwitchingOnEditingTest
│   │   │   │   ├── AdminDownloadableProductTypeSwitchingToSimpleProductTest.xml
│   │   │   │   └── AdminVirtualProductTypeSwitchingToDownloadableProductTest.xml
│   │   │   ├── AdminRemoveCustomOptionsFromProductTest.xml
│   │   │   ├── AdminRemoveDefaultImageSimpleProductTest.xml
│   │   │   ├── AdminRemoveDefaultImageVirtualProductTest.xml
│   │   │   ├── AdminRemoveImageAffectsAllScopesTest.xml
│   │   │   ├── AdminRemoveImageFromCategoryTest.xml
│   │   │   ├── AdminRemoveProductAttributeFromAttributeSetUsingDragAndDropTest.xml
│   │   │   ├── AdminRenameCategoryOnStoreViewLevelTest.xml
│   │   │   ├── AdminRequiredFieldsHaveRequiredFieldIndicatorTest.xml
│   │   │   ├── AdminRestrictedUserAddCategoryFromProductPageTest.xml
│   │   │   ├── AdminSaveProductByCustomDateWithCustomDateAttributeTest.xml
│   │   │   ├── AdminScopeSelectionShouldBeDisabledOnMediaGalleryProductAttributeEditTest.xml
│   │   │   ├── AdminShouldBeAbleToAssociateSimpleProductToWebsitesTest.xml
│   │   │   ├── AdminShowDoubleSpacesInProductGrid.xml
│   │   │   ├── AdminSimpleProductEditUiTest.xml
│   │   │   ├── AdminSimpleProductImagesTest
│   │   │   │   ├── AdminSimpleProductGifWithUnusedTransparencyImageTest.xml
│   │   │   │   ├── AdminSimpleProductImagesTest.xml
│   │   │   │   └── AdminSimpleProductRemoveImagesTest.xml
│   │   │   ├── AdminSimpleProductSetEditContentTest.xml
│   │   │   ├── AdminSimpleProductSetEditMetaDescriptionContentTest.xml
│   │   │   ├── AdminSimpleSetEditRelatedProductsTest.xml
│   │   │   ├── AdminSortingByWebsitesTest.xml
│   │   │   ├── AdminStoresAttributeSetNavigateMenuTest.xml
│   │   │   ├── AdminStoresProductNavigateMenuTest.xml
│   │   │   ├── AdminTestForRelatedProductsPriceBoxIsNotBeingUpdatedWhenNotNeeded.xml
│   │   │   ├── AdminTierPriceNotAvailableForProductOptionsWithoutTierPriceTest.xml
│   │   │   ├── AdminUnassignProductAttributeFromAttributeSetTest.xml
│   │   │   ├── AdminUpdateCategoryAndCheckDefaultUrlKeyOnStoreViewTest.xml
│   │   │   ├── AdminUpdateCategoryAndMakeInactiveTest.xml
│   │   │   ├── AdminUpdateCategoryNameWithStoreViewTest.xml
│   │   │   ├── AdminUpdateCategoryStoreUrlKeyTest.xml
│   │   │   ├── AdminUpdateCategoryUrlKeyWithStoreViewTest.xml
│   │   │   ├── AdminUpdateCategoryWithInactiveIncludeInMenuTest.xml
│   │   │   ├── AdminUpdateCategoryWithProductsDefaultSortingTest.xml
│   │   │   ├── AdminUpdateCategoryWithProductsTest.xml
│   │   │   ├── AdminUpdateFlatCategoryAndAddProductsTest.xml
│   │   │   ├── AdminUpdateFlatCategoryIncludeInNavigationTest.xml
│   │   │   ├── AdminUpdateFlatCategoryNameAndDescriptionTest.xml
│   │   │   ├── AdminUpdateOfSystemProductAttributeIsNotPossibleTest.xml
│   │   │   ├── AdminUpdateSimpleProductNameToVerifyDataOverridingOnStoreViewLevelTest.xml
│   │   │   ├── AdminUpdateSimpleProductPriceToVerifyDataOverridingOnStoreViewLevelTest.xml
│   │   │   ├── AdminUpdateSimpleProductTieredPriceTest.xml
│   │   │   ├── AdminUpdateSimpleProductWithRegularPriceInStockDisabledProductTest.xml
│   │   │   ├── AdminUpdateSimpleProductWithRegularPriceInStockEnabledFlatCatalogTest.xml
│   │   │   ├── AdminUpdateSimpleProductWithRegularPriceInStockEnabledFlatTest.xml
│   │   │   ├── AdminUpdateSimpleProductWithRegularPriceInStockNotVisibleIndividuallyTest.xml
│   │   │   ├── AdminUpdateSimpleProductWithRegularPriceInStockUnassignFromCategoryTest.xml
│   │   │   ├── AdminUpdateSimpleProductWithRegularPriceInStockVisibleInCatalogAndSearchTest.xml
│   │   │   ├── AdminUpdateSimpleProductWithRegularPriceInStockVisibleInCatalogOnlyTest.xml
│   │   │   ├── AdminUpdateSimpleProductWithRegularPriceInStockVisibleInSearchOnlyTest.xml
│   │   │   ├── AdminUpdateSimpleProductWithRegularPriceInStockWithCustomOptionsTest.xml
│   │   │   ├── AdminUpdateSimpleProductWithRegularPriceOutOfStockTest.xml
│   │   │   ├── AdminUpdateTopCategoryUrlWithNoRedirectTest.xml
│   │   │   ├── AdminUpdateTopCategoryUrlWithRedirectTest.xml
│   │   │   ├── AdminUpdateVirtualProductWithRegularPriceInStockVisibleInCategoryOnlyTest.xml
│   │   │   ├── AdminUpdateVirtualProductWithRegularPriceInStockWithCustomOptionsVisibleInSearchOnlyTest.xml
│   │   │   ├── AdminUpdateVirtualProductWithRegularPriceOutOfStockVisibleInCategoryAndSearchTest.xml
│   │   │   ├── AdminUpdateVirtualProductWithRegularPriceOutOfStockVisibleInCategoryOnlyTest.xml
│   │   │   ├── AdminUpdateVirtualProductWithRegularPriceOutOfStockVisibleInSearchOnlyTest.xml
│   │   │   ├── AdminUpdateVirtualProductWithSpecialPriceInStockVisibleInCategoryAndSearchTest.xml
│   │   │   ├── AdminUpdateVirtualProductWithSpecialPriceOutOfStockVisibleInCategoryAndSearchTest.xml
│   │   │   ├── AdminUpdateVirtualProductWithTierPriceInStockVisibleInCategoryAndSearchTest.xml
│   │   │   ├── AdminUpdateVirtualProductWithTierPriceInStockVisibleInCategoryOnlyTest.xml
│   │   │   ├── AdminUpdateVirtualProductWithTierPriceOutOfStockVisibleInCategoryAndSearchTest.xml
│   │   │   ├── AdminValidateAllNestedCategoryInWidgetTest.xml
│   │   │   ├── AdminValidateProductPricesOnTheFrontendWithTierPricingSetupTest.xml
│   │   │   ├── AdminValidateRelatedUpsellCrossSellPositionValueInProductExportCsvTest.xml
│   │   │   ├── AdminValidateSimpleProductWithCustomOptionsDragNDropPerPageTest.xml
│   │   │   ├── AdminValidateSimpleProductWithCustomOptionsPerPageTest.xml
│   │   │   ├── AdminVerifyCreateCloseCreateCustomProductAttributeTest.xml
│   │   │   ├── AdminVerifyCreateCustomProductAttributeTest.xml
│   │   │   ├── AdminVerifyProductOrderTest.xml
│   │   │   ├── AdminVirtualProductSetEditContentTest.xml
│   │   │   ├── AdminVirtualSetEditRelatedProductsTest.xml
│   │   │   ├── AdvanceCatalogSearchSimpleProductTest
│   │   │   │   ├── AdvanceCatalogSearchSimpleProductByDescriptionTest.xml
│   │   │   │   ├── AdvanceCatalogSearchSimpleProductByNameTest.xml
│   │   │   │   ├── AdvanceCatalogSearchSimpleProductByPriceTest.xml
│   │   │   │   ├── AdvanceCatalogSearchSimpleProductByShortDescriptionTest.xml
│   │   │   │   └── AdvanceCatalogSearchSimpleProductBySkuTest.xml
│   │   │   ├── AdvanceCatalogSearchVirtualProductTest
│   │   │   │   ├── AdvanceCatalogSearchVirtualProductByDescriptionTest.xml
│   │   │   │   ├── AdvanceCatalogSearchVirtualProductByNameTest.xml
│   │   │   │   ├── AdvanceCatalogSearchVirtualProductByPriceTest.xml
│   │   │   │   ├── AdvanceCatalogSearchVirtualProductByShortDescriptionTest.xml
│   │   │   │   └── AdvanceCatalogSearchVirtualProductBySkuTest.xml
│   │   │   ├── AlterAnchorCategoryTest.xml
│   │   │   ├── ChangeScopeForProductStatusAttributeTest.xml
│   │   │   ├── CheckTierPricingOfProductsTest.xml
│   │   │   ├── ConfigurableOptionTextInputLengthValidationHintTest.xml
│   │   │   ├── CreateAnchorCategoryTest.xml
│   │   │   ├── CreateProductAttributeEntityTest
│   │   │   │   ├── CreateBundleProductCustomAttributeEntityTextAreaTest.xml
│   │   │   │   ├── CreateProductAttributeEntityDateTest.xml
│   │   │   │   ├── CreateProductAttributeEntityDropdownTest.xml
│   │   │   │   ├── CreateProductAttributeEntityDropdownWithSingleQuoteTest.xml
│   │   │   │   ├── CreateProductAttributeEntityMultiSelectTest.xml
│   │   │   │   ├── CreateProductAttributeEntityPriceTest.xml
│   │   │   │   ├── CreateProductAttributeEntityTextFieldTest.xml
│   │   │   │   └── CreateProductAttributeEntityWithReservedKeysTest.xml
│   │   │   ├── DeleteCategoriesTest.xml
│   │   │   ├── DeleteUsedInConfigurableProductAttributeTest.xml
│   │   │   ├── DisplayRefreshCacheAfterChangingCategoryPageLayoutTest.xml
│   │   │   ├── DisplayingCustomAttributesInProductGridTest.xml
│   │   │   ├── EnablingManageStockTest.xml
│   │   │   ├── EndToEndB2CAdminTest.xml
│   │   │   ├── EndToEndB2CGuestUserTest
│   │   │   │   └── EndToEndB2CGuestUserTest.xml
│   │   │   ├── EndToEndB2CLoggedInUserTest.xml
│   │   │   ├── NewProductsListWidgetSimpleProductTest.xml
│   │   │   ├── NewProductsListWidgetVirtualProductTest.xml
│   │   │   ├── ProductAttributeWithoutValueInCompareListTest.xml
│   │   │   ├── ProductAvailableAfterEnablingSubCategoriesTest.xml
│   │   │   ├── ProductViewPageCustomOptionValidationErrorMessageTest.xml
│   │   │   ├── SaveProductWithCustomOptionsAdditionalWebsiteTest.xml
│   │   │   ├── SavingCustomAttributeValuesUsingUITest.xml
│   │   │   ├── SimpleProductTwoCustomOptionsTest.xml
│   │   │   ├── SpecialPriceCheckOnWishListPageTest.xml
│   │   │   ├── StoreFrontAddRelatedandUpsellstoCartfromproductpageTest.xml
│   │   │   ├── StoreFrontAssertProductFinalPriceChangesDynamicallyOnProductPageWithTierPricesConfiguredTest.xml
│   │   │   ├── StoreFrontProductsDisplayUsingElasticSearchTest.xml
│   │   │   ├── StoreFrontRecentlyViewedAtStoreLevelTest.xml
│   │   │   ├── StoreFrontRecentlyViewedAtStoreViewLevelTest.xml
│   │   │   ├── StoreFrontSimpleProductWithSpecialAndTierDiscountPriceTest.xml
│   │   │   ├── StorefrontAddProductWithBackordersAllowedOnProductLevelToCartTest.xml
│   │   │   ├── StorefrontAdvanceCatalogSearchSimpleProductBySkuWithHyphenTest.xml
│   │   │   ├── StorefrontAdvanceCatalogSearchVirtualProductBySkuWithHyphenTest.xml
│   │   │   ├── StorefrontCatalogNavigationMenuUIDesktopTest.xml
│   │   │   ├── StorefrontCategoryHighlightedAndProductDisplayedTest.xml
│   │   │   ├── StorefrontCategoryPageWithCategoryFilterTest.xml
│   │   │   ├── StorefrontCategoryPageWithoutCategoryFilterTest.xml
│   │   │   ├── StorefrontCategorySidebarMobileMenuTest.xml
│   │   │   ├── StorefrontCheckCustomOptionPriceDifferentCurrencyTest.xml
│   │   │   ├── StorefrontCheckDefaultNumberProductsToDisplayTest.xml
│   │   │   ├── StorefrontCheckNoAppearDefaultOptionConfigurableProductTest.xml
│   │   │   ├── StorefrontCheckSpecialPriceWithCustomOptionAndTaxTest.xml
│   │   │   ├── StorefrontConfigurableOptionsThumbImagesTest.xml
│   │   │   ├── StorefrontEnsureThatAccordionAnchorIsVisibleOnViewportOnceClickedTest.xml
│   │   │   ├── StorefrontForthLevelCategoryTest.xml
│   │   │   ├── StorefrontFotoramaArrowsTest.xml
│   │   │   ├── StorefrontNoStoreCodeNoCategoryPathHtmlSuffixNavigationTest.xml
│   │   │   ├── StorefrontNoStoreCodeYesCategoryPathHtmlSuffixNavigationTest.xml
│   │   │   ├── StorefrontOnlyXProductLeftForSimpleProductsTest.xml
│   │   │   ├── StorefrontPaginationResetOnViewModeChange.xml
│   │   │   ├── StorefrontProductImageSlideTest.xml
│   │   │   ├── StorefrontProductImageWithDotTest.xml
│   │   │   ├── StorefrontProductNameWithDoubleQuoteTest
│   │   │   │   ├── StorefrontProductNameWithDoubleQuoteTest.xml
│   │   │   │   └── StorefrontProductNameWithHTMLEntitiesTest.xml
│   │   │   ├── StorefrontProductWithEmptyAttributeTest.xml
│   │   │   ├── StorefrontProductWithMediaGalleryBehaviorTest.xml
│   │   │   ├── StorefrontProductWithMediaThumbGallerySliderTest.xml
│   │   │   ├── StorefrontProductsCompareWithEmptyAttributeTest.xml
│   │   │   ├── StorefrontPurchaseProductCustomOptionsDifferentStoreViewsTest.xml
│   │   │   ├── StorefrontPurchaseProductWithCustomOptionsTest.xml
│   │   │   ├── StorefrontPurchaseProductWithCustomOptionsWithLongValuesTitleTest.xml
│   │   │   ├── StorefrontRememberCategoryPaginationTest.xml
│   │   │   ├── StorefrontRemoveProductFromCompareSidebarTest.xml
│   │   │   ├── StorefrontSelectedByQueryParamsConfigurableOptionsThumbImagesTest.xml
│   │   │   ├── StorefrontSpecialPriceForDifferentTimezonesForWebsitesTest.xml
│   │   │   ├── StorefrontVerifyCategoryPageNotCachedTest.xml
│   │   │   ├── StorefrontVerifyCategoryProductAndProductCategoryPartialReindexTest.xml
│   │   │   ├── StorefrontVerifyCompareListVisibilityForMultiWebsiteTest.xml
│   │   │   ├── StorefrontVerifyProductAfterPartialReindexOnSeveralWebsitesTest.xml
│   │   │   ├── StorefrontVerifyThatRecentlyOrderedWidgetShowOnlyFiveProductTest.xml
│   │   │   ├── StorefrontYesStoreCodeNoCategoryPathNoSuffixNavigationTest.xml
│   │   │   ├── StorefrontYesStoreCodeYesCategoryPathNoSuffixNavigationTest.xml
│   │   │   ├── TierPricingWhenPriceScopeIsWebsiteWorkingProperlyWithMultipleCurrenciesConfiguredTest.xml
│   │   │   ├── TieredPricingAndQuantityIncrementsWorkWithDecimalinventoryTest.xml
│   │   │   ├── VerifyCategoryProductAndProductCategoryPartialReindexTest.xml
│   │   │   ├── VerifyChildCategoriesShouldNotIncludeInMenuTest.xml
│   │   │   ├── VerifyDefaultWYSIWYGToolbarOnProductTest
│   │   │   │   ├── VerifyDefaultWYSIWYGToolbarOnProductTest.xml
│   │   │   │   └── VerifydefaultcontrolsonproductshortdescriptionTest.xml
│   │   │   ├── VerifyTheVisibilityOfTheProductImageWithAndWithoutTheOptionHideFromProductPageTest.xml
│   │   │   ├── VerifyTinyMCEIsNativeWYSIWYGOnCatalogTest.xml
│   │   │   └── VerifyTinyMCEIsNativeWYSIWYGOnProductTest.xml
│   │   ├── test-dependency-allowlist
│   │   └── test-dependency-errors-detailed
│   └── Unit
│       ├── Block
│       │   ├── Adminhtml
│       │   │   ├── Category
│       │   │   │   └── AbstractCategoryTest.php
│       │   │   ├── Product
│       │   │   │   ├── Attribute
│       │   │   │   │   ├── Button
│       │   │   │   │   │   ├── CancelTest.php
│       │   │   │   │   │   ├── GenericTest.php
│       │   │   │   │   │   └── SaveTest.php
│       │   │   │   │   ├── Edit
│       │   │   │   │   │   └── Tab
│       │   │   │   │   │       └── AdvancedTest.php
│       │   │   │   │   └── GridTest.php
│       │   │   │   ├── Composite
│       │   │   │   │   └── Fieldset
│       │   │   │   │       └── OptionsTest.php
│       │   │   │   ├── Edit
│       │   │   │   │   ├── Action
│       │   │   │   │   │   └── Attribute
│       │   │   │   │   │       └── Tab
│       │   │   │   │   │           └── InventoryTest.php
│       │   │   │   │   ├── Button
│       │   │   │   │   │   ├── AddAttributeTest.php
│       │   │   │   │   │   ├── BackTest.php
│       │   │   │   │   │   ├── CreateCategoryTest.php
│       │   │   │   │   │   ├── GenericTest.php
│       │   │   │   │   │   └── SaveTest.php
│       │   │   │   │   └── Tab
│       │   │   │   │       ├── AlertsTest.php
│       │   │   │   │       └── InventoryTest.php
│       │   │   │   ├── Helper
│       │   │   │   │   └── Form
│       │   │   │   │       ├── CategoryTest.php
│       │   │   │   │       ├── GalleryTest.php
│       │   │   │   │       └── WeightTest.php
│       │   │   │   └── Options
│       │   │   │       └── AjaxTest.php
│       │   │   └── Rss
│       │   │       ├── Grid
│       │   │       │   └── LinkTest.php
│       │   │       └── NotifyStockTest.php
│       │   ├── Category
│       │   │   ├── Plugin
│       │   │   │   └── PriceBoxTagsTest.php
│       │   │   ├── Rss
│       │   │   │   └── LinkTest.php
│       │   │   └── ViewTest.php
│       │   ├── FrontendStorageManagerTest.php
│       │   ├── NavigationTest.php
│       │   ├── Product
│       │   │   ├── AbstractProductTest.php
│       │   │   ├── Compare
│       │   │   │   └── ListCompareTest.php
│       │   │   ├── ContextTest.php
│       │   │   ├── ImageFactoryTest.php
│       │   │   ├── ListProductTest.php
│       │   │   ├── ListTest.php
│       │   │   ├── NewProductTest.php
│       │   │   ├── PriceTest.php
│       │   │   ├── ProductList
│       │   │   │   ├── RelatedTest.php
│       │   │   │   ├── ToolbarTest.php
│       │   │   │   └── UpsellTest.php
│       │   │   ├── View
│       │   │   │   ├── AttributesTest.php
│       │   │   │   ├── GalleryOptionsTest.php
│       │   │   │   ├── GalleryTest.php
│       │   │   │   ├── OptionsTest.php
│       │   │   │   └── TabsTest.php
│       │   │   ├── ViewTest.php
│       │   │   └── Widget
│       │   │       └── NewWidgetTest.php
│       │   ├── Rss
│       │   │   ├── CategoryTest.php
│       │   │   └── Product
│       │   │       ├── NewProductsTest.php
│       │   │       └── SpecialTest.php
│       │   ├── Ui
│       │   │   └── ProductViewCounterTest.php
│       │   └── Widget
│       │       └── LinkTest.php
│       ├── Controller
│       │   ├── Adminhtml
│       │   │   ├── Category
│       │   │   │   ├── DeleteTest.php
│       │   │   │   ├── EditTest.php
│       │   │   │   ├── Image
│       │   │   │   │   └── UploadTest.php
│       │   │   │   ├── MoveTest.php
│       │   │   │   ├── RefreshPathTest.php
│       │   │   │   ├── SaveTest.php
│       │   │   │   └── Widget
│       │   │   │       ├── CategoriesJsonTest.php
│       │   │   │       └── ChooserTest.php
│       │   │   ├── Product
│       │   │   │   ├── Action
│       │   │   │   │   └── Attribute
│       │   │   │   │       └── EditTest.php
│       │   │   │   ├── AddAttributeToTemplateTest.php
│       │   │   │   ├── Attribute
│       │   │   │   │   ├── EditTest.php
│       │   │   │   │   ├── SaveTest.php
│       │   │   │   │   └── ValidateTest.php
│       │   │   │   ├── AttributeTest.php
│       │   │   │   ├── BuilderTest.php
│       │   │   │   ├── Initialization
│       │   │   │   │   ├── Helper
│       │   │   │   │   │   ├── AttributeFilterTest.php
│       │   │   │   │   │   ├── HandlerFactoryTest.php
│       │   │   │   │   │   └── Plugin
│       │   │   │   │   │       └── Handler
│       │   │   │   │   │           └── CompositeTest.php
│       │   │   │   │   ├── HelperTest.php
│       │   │   │   │   └── StockDataFilterTest.php
│       │   │   │   ├── MassStatusTest.php
│       │   │   │   ├── NewActionTest.php
│       │   │   │   ├── ReloadTest.php
│       │   │   │   ├── SaveTest.php
│       │   │   │   ├── ShowUpdateResultTest.php
│       │   │   │   └── ValidateTest.php
│       │   │   └── ProductTest.php
│       │   ├── Category
│       │   │   └── ViewTest.php
│       │   └── Product
│       │       ├── Compare
│       │       │   └── IndexTest.php
│       │       ├── Frontend
│       │       │   └── Action
│       │       │       └── SynchronizeTest.php
│       │       └── ViewTest.php
│       ├── Cron
│       │   ├── DeleteAbandonedStoreFlatTablesTest.php
│       │   ├── DeleteOutdatedPriceValuesTest.php
│       │   ├── FrontendActionsFlushTest.php
│       │   ├── RefreshSpecialPricesTest.php
│       │   └── SynchronizeWebsiteAttributesTest.php
│       ├── CustomerData
│       │   ├── CompareProductsTest.php
│       │   ├── ProductFrontendActionSectionTest.php
│       │   └── ProductsRenderInfoSectionTest.php
│       ├── Helper
│       │   ├── ImageTest.php
│       │   ├── Product
│       │   │   ├── CompareTest.php
│       │   │   ├── ConfigurationPoolTest.php
│       │   │   ├── ConfigurationTest.php
│       │   │   ├── Edit
│       │   │   │   └── Action
│       │   │   │       └── AttributeTest.php
│       │   │   ├── Flat
│       │   │   │   └── IndexerTest.php
│       │   │   └── ProductListTest.php
│       │   └── ProductTest.php
│       ├── Model
│       │   ├── Api
│       │   │   └── SearchCriteria
│       │   │       └── CollectionProcessor
│       │   │           ├── ConditionProcessor
│       │   │           │   └── ConditionBuilder
│       │   │           │       └── FactoryTest.php
│       │   │           └── FilterProcessor
│       │   │               ├── ProductCategoryFilterTest.php
│       │   │               └── ProductWebsiteFilterTest.php
│       │   ├── Attribute
│       │   │   ├── Backend
│       │   │   │   ├── DefaultBackendTest.php
│       │   │   │   └── TierPrice
│       │   │   │       ├── SaveHandlerTest.php
│       │   │   │       └── UpdateHandlerTest.php
│       │   │   ├── Config
│       │   │   │   ├── ConverterTest.php
│       │   │   │   ├── ReaderTest.php
│       │   │   │   ├── SchemaLocatorTest.php
│       │   │   │   ├── XsdTest.php
│       │   │   │   └── _files
│       │   │   │       ├── attributes_config_merged.php
│       │   │   │       ├── attributes_config_merged.xml
│       │   │   │       ├── attributes_config_one.xml
│       │   │   │       └── attributes_config_two.xml
│       │   │   ├── ConfigTest.php
│       │   │   └── LockValidatorCompositeTest.php
│       │   ├── Category
│       │   │   ├── Attribute
│       │   │   │   ├── Backend
│       │   │   │   │   ├── ImageTest.php
│       │   │   │   │   └── SortbyTest.php
│       │   │   │   └── Source
│       │   │   │       ├── LayoutTest.php
│       │   │   │       ├── PageTest.php
│       │   │   │       └── SortbyTest.php
│       │   │   ├── AttributeRepositoryTest.php
│       │   │   ├── DataProviderTest.php
│       │   │   ├── FileInfoTest.php
│       │   │   ├── ImageTest.php
│       │   │   ├── Link
│       │   │   │   ├── ReadHandlerTest.php
│       │   │   │   └── SaveHandlerTest.php
│       │   │   ├── Product
│       │   │   │   └── PositionResolverTest.php
│       │   │   └── TreeTest.php
│       │   ├── CategoryLinkManagementTest.php
│       │   ├── CategoryLinkRepositoryTest.php
│       │   ├── CategoryListTest.php
│       │   ├── CategoryManagementTest.php
│       │   ├── CategoryRepositoryTest.php
│       │   ├── CategoryTest.php
│       │   ├── CollectionProviderTest.php
│       │   ├── Config
│       │   │   ├── CatalogClone
│       │   │   │   └── Media
│       │   │   │       └── ImageTest.php
│       │   │   └── Source
│       │   │       ├── CategoryTest.php
│       │   │       ├── GridPerPageTest.php
│       │   │       ├── ListPerPageTest.php
│       │   │       ├── ListSortTest.php
│       │   │       └── Product
│       │   │           └── Options
│       │   │               └── TypeTest.php
│       │   ├── ConfigTest.php
│       │   ├── CustomOptions
│       │   │   ├── CustomOptionProcessorTest.php
│       │   │   └── CustomOptionTest.php
│       │   ├── Entity
│       │   │   └── AttributeTest.php
│       │   ├── FactoryTest.php
│       │   ├── FrontendStorageConfigurationPoolTest.php
│       │   ├── ImageExtractorTest.php
│       │   ├── Indexer
│       │   │   ├── Category
│       │   │   │   ├── Flat
│       │   │   │   │   ├── Plugin
│       │   │   │   │   │   ├── IndexerConfigDataTest.php
│       │   │   │   │   │   ├── StoreGroupTest.php
│       │   │   │   │   │   └── StoreViewTest.php
│       │   │   │   │   ├── StateTest.php
│       │   │   │   │   └── System
│       │   │   │   │       └── Config
│       │   │   │   │           └── ModeTest.php
│       │   │   │   ├── FlatTest.php
│       │   │   │   ├── Product
│       │   │   │   │   ├── Action
│       │   │   │   │   │   └── RowsTest.php
│       │   │   │   │   ├── Plugin
│       │   │   │   │   │   ├── MviewStateTest.php
│       │   │   │   │   │   ├── StoreGroupTest.php
│       │   │   │   │   │   ├── StoreViewTest.php
│       │   │   │   │   │   └── TableResolverTest.php
│       │   │   │   │   └── RowSizeEstimatorTest.php
│       │   │   │   └── ProductTest.php
│       │   │   └── Product
│       │   │       ├── Category
│       │   │       │   └── Action
│       │   │       │       └── RowsTest.php
│       │   │       ├── CategoryTest.php
│       │   │       ├── Eav
│       │   │       │   ├── AbstractActionTest.php
│       │   │       │   ├── Action
│       │   │       │   │   ├── FullTest.php
│       │   │       │   │   ├── RowTest.php
│       │   │       │   │   └── RowsTest.php
│       │   │       │   └── Plugin
│       │   │       │       ├── AttributeSet
│       │   │       │       │   └── IndexableAttributeFilterTest.php
│       │   │       │       ├── AttributeSetTest.php
│       │   │       │       ├── ImportTest.php
│       │   │       │       └── StoreViewTest.php
│       │   │       ├── EavTest.php
│       │   │       ├── Flat
│       │   │       │   ├── Action
│       │   │       │   │   ├── EraserTest.php
│       │   │       │   │   ├── RowTest.php
│       │   │       │   │   ├── Rows
│       │   │       │   │   │   └── TableDataTest.php
│       │   │       │   │   └── RowsTest.php
│       │   │       │   ├── FlatTableBuilderTest.php
│       │   │       │   ├── Plugin
│       │   │       │   │   ├── IndexerConfigDataTest.php
│       │   │       │   │   ├── StoreGroupTest.php
│       │   │       │   │   └── StoreTest.php
│       │   │       │   ├── ProcessorTest.php
│       │   │       │   ├── StateTest.php
│       │   │       │   ├── System
│       │   │       │   │   └── Config
│       │   │       │   │       └── ModeTest.php
│       │   │       │   ├── Table
│       │   │       │   │   └── BuilderTest.php
│       │   │       │   └── TableDataTest.php
│       │   │       ├── FlatTest.php
│       │   │       ├── FullTest.php
│       │   │       └── Price
│       │   │           ├── Action
│       │   │           │   ├── RowDefaultPriceIndexerTest.php
│       │   │           │   ├── RowTest.php
│       │   │           │   └── RowsTest.php
│       │   │           ├── CustomOptionPriceModifierTest.php
│       │   │           ├── Plugin
│       │   │           │   ├── CustomerGroupTest.php
│       │   │           │   └── WebsiteTest.php
│       │   │           └── System
│       │   │               └── Config
│       │   │                   └── PriceScopeTest.php
│       │   ├── Layer
│       │   │   ├── Category
│       │   │   │   ├── AvailabilityFlagTest.php
│       │   │   │   ├── CollectionFilterTest.php
│       │   │   │   ├── FilterableAttributeListTest.php
│       │   │   │   └── StateKeyTest.php
│       │   │   ├── Filter
│       │   │   │   ├── AttributeTest.php
│       │   │   │   ├── CategoryTest.php
│       │   │   │   ├── DataProvider
│       │   │   │   │   ├── CategoryTest.php
│       │   │   │   │   ├── DecimalTest.php
│       │   │   │   │   └── PriceTest.php
│       │   │   │   ├── DecimalTest.php
│       │   │   │   ├── FactoryTest.php
│       │   │   │   ├── Item
│       │   │   │   │   └── DataBuilderTest.php
│       │   │   │   └── PriceTest.php
│       │   │   ├── FilterListTest.php
│       │   │   ├── Search
│       │   │   │   ├── CollectionFilterTest.php
│       │   │   │   ├── FilterableAttributeListTest.php
│       │   │   │   └── StateKeyTest.php
│       │   │   └── StateTest.php
│       │   ├── LayerTest.php
│       │   ├── Layout
│       │   │   └── DepersonalizePluginTest.php
│       │   ├── Locator
│       │   │   └── RegistryLocatorTest.php
│       │   ├── Plugin
│       │   │   ├── LogTest.php
│       │   │   ├── ProductRepository
│       │   │   │   └── TransactionWrapperTest.php
│       │   │   └── QuoteItemProductOptionTest.php
│       │   ├── Product
│       │   │   ├── ActionTest.php
│       │   │   ├── Attribute
│       │   │   │   ├── AttributeSetFinderTest.php
│       │   │   │   ├── Backend
│       │   │   │   │   ├── BooleanTest.php
│       │   │   │   │   ├── CategoryTest.php
│       │   │   │   │   ├── GroupPrice
│       │   │   │   │   │   └── AbstractTest.php
│       │   │   │   │   ├── Media
│       │   │   │   │   │   ├── EntryConverterPoolTest.php
│       │   │   │   │   │   └── ImageEntryConverterTest.php
│       │   │   │   │   ├── PriceTest.php
│       │   │   │   │   ├── StockTest.php
│       │   │   │   │   ├── TierpriceTest.php
│       │   │   │   │   └── WeightTest.php
│       │   │   │   ├── Frontend
│       │   │   │   │   ├── ImageTest.php
│       │   │   │   │   └── InputType
│       │   │   │   │       └── PresentationTest.php
│       │   │   │   ├── GroupTest.php
│       │   │   │   ├── ManagementTest.php
│       │   │   │   ├── OptionManagementTest.php
│       │   │   │   ├── RepositoryTest.php
│       │   │   │   ├── SetManagementTest.php
│       │   │   │   ├── SetRepositoryTest.php
│       │   │   │   ├── Source
│       │   │   │   │   ├── BooleanTest.php
│       │   │   │   │   ├── CountryofmanufactureTest.php
│       │   │   │   │   ├── InputtypeTest.php
│       │   │   │   │   ├── LayoutTest.php
│       │   │   │   │   └── StatusTest.php
│       │   │   │   └── TypesListTest.php
│       │   │   ├── CartConfigurationTest.php
│       │   │   ├── CatalogPriceTest.php
│       │   │   ├── Compare
│       │   │   │   └── ItemTest.php
│       │   │   ├── ConditionTest.php
│       │   │   ├── CopyConstructor
│       │   │   │   ├── CompositeTest.php
│       │   │   │   ├── CrossSellTest.php
│       │   │   │   ├── RelatedTest.php
│       │   │   │   └── UpSellTest.php
│       │   │   ├── CopyConstructorFactoryTest.php
│       │   │   ├── Filter
│       │   │   │   └── DateTimeTest.php
│       │   │   ├── Gallery
│       │   │   │   ├── GalleryManagementTest.php
│       │   │   │   ├── MimeTypeExtensionMapTest.php
│       │   │   │   └── ProcessorTest.php
│       │   │   ├── Image
│       │   │   │   ├── CacheTest.php
│       │   │   │   ├── ConvertImageMiscParamsToReadableFormatTest.php
│       │   │   │   ├── ParamsBuilderTest.php
│       │   │   │   └── RemoveDeletedImagesFromCacheTest.php
│       │   │   ├── ImageTest.php
│       │   │   ├── Initialization
│       │   │   │   └── Helper
│       │   │   │       └── ProductLinksTest.php
│       │   │   ├── Link
│       │   │   │   ├── ConverterTest.php
│       │   │   │   └── ResolverTest.php
│       │   │   ├── LinkTest.php
│       │   │   ├── LinkTypeProviderTest.php
│       │   │   ├── Media
│       │   │   │   └── AttributeManagementTest.php
│       │   │   ├── Option
│       │   │   │   ├── RepositoryTest.php
│       │   │   │   ├── SaveHandlerTest.php
│       │   │   │   ├── Type
│       │   │   │   │   ├── FactoryTest.php
│       │   │   │   │   └── FileTest.php
│       │   │   │   ├── UrlBuilderTest.php
│       │   │   │   ├── Validator
│       │   │   │   │   ├── DefaultValidatorTest.php
│       │   │   │   │   ├── FileTest.php
│       │   │   │   │   ├── PoolTest.php
│       │   │   │   │   ├── SelectTest.php
│       │   │   │   │   └── TextTest.php
│       │   │   │   └── ValueTest.php
│       │   │   ├── OptionTest.php
│       │   │   ├── Price
│       │   │   │   ├── BasePriceStorageTest.php
│       │   │   │   ├── CostStorageTest.php
│       │   │   │   ├── PricePersistenceTest.php
│       │   │   │   ├── SpecialPriceStorageTest.php
│       │   │   │   ├── TierPriceFactoryTest.php
│       │   │   │   ├── TierPriceStorageTest.php
│       │   │   │   └── Validation
│       │   │   │       ├── InvalidSkuProcessorTest.php
│       │   │   │       ├── ResultTest.php
│       │   │   │       └── TierPriceValidatorTest.php
│       │   │   ├── PriceModifier
│       │   │   │   └── CompositeTest.php
│       │   │   ├── PriceModifierTest.php
│       │   │   ├── Pricing
│       │   │   │   └── Renderer
│       │   │   │       └── SalableResolverTest.php
│       │   │   ├── ProductFrontendAction
│       │   │   │   └── SynchronizerTest.php
│       │   │   ├── ProductList
│       │   │   │   └── ToolbarTest.php
│       │   │   ├── ReservedAttributeListTest.php
│       │   │   ├── TierPriceManagementTest.php
│       │   │   ├── Type
│       │   │   │   ├── AbstractTypeTest.php
│       │   │   │   ├── PriceTest.php
│       │   │   │   ├── SimpleTest.php
│       │   │   │   └── VirtualTest.php
│       │   │   ├── TypeTest.php
│       │   │   ├── TypeTransitionManagerTest.php
│       │   │   ├── UrlTest.php
│       │   │   ├── ValidatorTest.php
│       │   │   ├── VisibilityTest.php
│       │   │   ├── Webapi
│       │   │   │   ├── ProductOutputProcessorTest.php
│       │   │   │   └── Rest
│       │   │   │       └── RequestTypeBasedDeserializerTest.php
│       │   │   └── Website
│       │   │       ├── ReadHandlerTest.php
│       │   │       └── SaveHandlerTest.php
│       │   ├── ProductAttributeGroupRepositoryTest.php
│       │   ├── ProductIdLocatorTest.php
│       │   ├── ProductLink
│       │   │   ├── ManagementTest.php
│       │   │   └── RepositoryTest.php
│       │   ├── ProductManagementTest.php
│       │   ├── ProductOptionProcessorTest.php
│       │   ├── ProductOptions
│       │   │   └── Config
│       │   │       ├── XsdTest.php
│       │   │       └── _files
│       │   │           ├── invalidProductOptionsMergedXmlArray.php
│       │   │           ├── invalidProductOptionsXmlArray.php
│       │   │           ├── product_options_merged_valid.xml
│       │   │           └── product_options_valid.xml
│       │   ├── ProductRender
│       │   │   ├── FormattedPriceInfoBuilderTest.php
│       │   │   └── PriceInfoTest.php
│       │   ├── ProductRenderListTest.php
│       │   ├── ProductRepository
│       │   │   └── MediaGalleryProcessorTest.php
│       │   ├── ProductRepositoryTest.php
│       │   ├── ProductTest.php
│       │   ├── ProductTypeListTest.php
│       │   ├── ProductTypes
│       │   │   ├── Config
│       │   │   │   ├── ConverterTest.php
│       │   │   │   ├── SchemaLocatorTest.php
│       │   │   │   ├── XsdMergedTest.php
│       │   │   │   ├── XsdTest.php
│       │   │   │   └── _files
│       │   │   │       ├── invalidProductTypesMergedXmlArray.php
│       │   │   │       ├── invalidProductTypesXmlArray.php
│       │   │   │       ├── product_types.php
│       │   │   │       ├── product_types.xml
│       │   │   │       ├── valid_product_types.xml
│       │   │   │       └── valid_product_types_merged.xml
│       │   │   └── ConfigTest.php
│       │   ├── ResourceModel
│       │   │   ├── AbstractTest.php
│       │   │   ├── Attribute
│       │   │   │   └── ConditionBuilderTest.php
│       │   │   ├── AttributeTest.php
│       │   │   ├── Category
│       │   │   │   ├── AggregateCountTest.php
│       │   │   │   ├── Collection
│       │   │   │   │   └── FactoryTest.php
│       │   │   │   ├── FlatTest.php
│       │   │   │   └── TreeTest.php
│       │   │   ├── CategoryTest.php
│       │   │   ├── ConfigTest.php
│       │   │   ├── Eav
│       │   │   │   └── AttributeTest.php
│       │   │   ├── Indexer
│       │   │   │   └── ActiveTableSwitcherTest.php
│       │   │   ├── MediaImageDeleteProcessorTest.php
│       │   │   ├── Product
│       │   │   │   ├── ActionTest.php
│       │   │   │   ├── CategoryLinkTest.php
│       │   │   │   ├── Collection
│       │   │   │   │   ├── JoinMinimalPositionTest.php
│       │   │   │   │   └── ProductLimitationTest.php
│       │   │   │   ├── CollectionTest.php
│       │   │   │   ├── CompositeBaseSelectProcessorTest.php
│       │   │   │   ├── FlatTest.php
│       │   │   │   ├── GalleryTest.php
│       │   │   │   ├── ImageTest.php
│       │   │   │   ├── Indexer
│       │   │   │   │   ├── Eav
│       │   │   │   │   │   ├── BatchSizeCalculatorTest.php
│       │   │   │   │   │   ├── DecimalRowSizeEstimatorTest.php
│       │   │   │   │   │   └── SourceTest.php
│       │   │   │   │   ├── LinkedProductSelectBuilderByIndexPriceTest.php
│       │   │   │   │   ├── Price
│       │   │   │   │   │   ├── BatchSizeCalculatorTest.php
│       │   │   │   │   │   ├── CompositeProductBatchSizeAdjusterTest.php
│       │   │   │   │   │   ├── CompositeProductRelationsCalculatorTest.php
│       │   │   │   │   │   ├── CompositeProductRowSizeEstimatorTest.php
│       │   │   │   │   │   ├── DefaultPriceTest.php
│       │   │   │   │   │   └── IndexTableRowSizeEstimatorTest.php
│       │   │   │   │   └── TemporaryTableStrategyTest.php
│       │   │   │   ├── Link
│       │   │   │   │   └── Product
│       │   │   │   │       └── CollectionTest.php
│       │   │   │   ├── LinkTest.php
│       │   │   │   ├── Option
│       │   │   │   │   └── CollectionTest.php
│       │   │   │   ├── StatusBaseSelectProcessorTest.php
│       │   │   │   └── Website
│       │   │   │       └── LinkTest.php
│       │   │   ├── ProductTest.php
│       │   │   └── ProductWebsiteAssignmentHandlerTest.php
│       │   ├── Rss
│       │   │   ├── CategoryTest.php
│       │   │   └── Product
│       │   │       ├── NewProductsTest.php
│       │   │       ├── NotifyStockTest.php
│       │   │       └── SpecialTest.php
│       │   ├── System
│       │   │   └── Config
│       │   │       ├── Backend
│       │   │       │   ├── Catalog
│       │   │       │   │   └── Url
│       │   │       │   │       └── Rewrite
│       │   │       │   │           └── SuffixTest.php
│       │   │       │   └── Rss
│       │   │       │       └── CategoryTest.php
│       │   │       └── Source
│       │   │           └── InputtypeTest.php
│       │   ├── Template
│       │   │   └── Filter
│       │   │       └── FactoryTest.php
│       │   ├── View
│       │   │   └── Asset
│       │   │       └── PlaceholderTest.php
│       │   └── _files
│       │       ├── converted_view.php
│       │       └── valid_view.xml
│       ├── Observer
│       │   ├── ImageResizeAfterProductSaveTest.php
│       │   ├── MenuCategoryDataTest.php
│       │   ├── SetSpecialPriceStartDateTest.php
│       │   └── SynchronizeWebsiteAttributesOnStoreChangeTest.php
│       ├── Plugin
│       │   ├── Block
│       │   │   └── TopmenuTest.php
│       │   └── Model
│       │       ├── Attribute
│       │       │   └── Backend
│       │       │       └── AttributeValidationTest.php
│       │       ├── AttributeSetRepository
│       │       │   └── RemoveProductsTest.php
│       │       ├── Indexer
│       │       │   └── Category
│       │       │       └── Product
│       │       │           └── ExecuteTest.php
│       │       ├── Product
│       │       │   └── Action
│       │       │       └── UpdateAttributesFlushCacheTest.php
│       │       └── ResourceModel
│       │           ├── Attribute
│       │           │   └── SaveTest.php
│       │           └── ConfigTest.php
│       ├── Pricing
│       │   ├── Price
│       │   │   ├── BasePriceTest.php
│       │   │   ├── ConfiguredPriceTest.php
│       │   │   ├── CustomOptionPriceTest.php
│       │   │   ├── FinalPriceTest.php
│       │   │   ├── MinimalTierPriceCalculatorTest.php
│       │   │   ├── RegularPriceTest.php
│       │   │   ├── SpecialPriceTest.php
│       │   │   └── TierPriceTest.php
│       │   ├── Render
│       │   │   ├── FinalPriceBoxTest.php
│       │   │   └── PriceBoxTest.php
│       │   └── RenderTest.php
│       ├── Setup
│       │   ├── CategorySetupTest.php
│       │   └── Patch
│       │       └── Data
│       │           └── UpdateMultiselectAttributesBackendTypesTest.php
│       ├── Ui
│       │   ├── AllowedProductTypesTest.php
│       │   ├── Component
│       │   │   ├── ColumnFactoryTest.php
│       │   │   ├── FilterFactoryTest.php
│       │   │   ├── Listing
│       │   │   │   └── Columns
│       │   │   │       ├── AbstractColumnTest.php
│       │   │   │       ├── AttributeSetTextTest.php
│       │   │   │       ├── PriceTest.php
│       │   │   │       └── StatusTextTest.php
│       │   │   └── Product
│       │   │       ├── Form
│       │   │       │   └── Categories
│       │   │       │       └── OptionsTest.php
│       │   │       └── MassActionTest.php
│       │   └── DataProvider
│       │       ├── CatalogEavValidationRulesTest.php
│       │       └── Product
│       │           ├── Form
│       │           │   ├── Modifier
│       │           │   │   ├── AbstractModifierTest.php
│       │           │   │   ├── AdvancedPricingTest.php
│       │           │   │   ├── AttributeSetTest.php
│       │           │   │   ├── AttributesTest.php
│       │           │   │   ├── CategoriesTest.php
│       │           │   │   ├── CurrencySymbolProviderTest.php
│       │           │   │   ├── CustomOptionsTest.php
│       │           │   │   ├── EavTest.php
│       │           │   │   ├── FactoryTest.php
│       │           │   │   ├── GeneralTest.php
│       │           │   │   ├── ImagesTest.php
│       │           │   │   ├── RelatedTest.php
│       │           │   │   ├── ScheduleDesignUpdateTest.php
│       │           │   │   ├── SystemTest.php
│       │           │   │   ├── TierPriceTest.php
│       │           │   │   └── WebsitesTest.php
│       │           │   ├── NewCategoryDataProviderTest.php
│       │           │   └── ProductDataProviderTest.php
│       │           ├── Listing
│       │           │   └── Collector
│       │           │       ├── AdditionalInfoTest.php
│       │           │       ├── ImageTest.php
│       │           │       ├── PriceTest.php
│       │           │       └── UrlTest.php
│       │           ├── Modifier
│       │           │   └── PriceAttributesTest.php
│       │           ├── ProductCustomOptionsDataProviderTest.php
│       │           └── Related
│       │               ├── AbstractDataProviderTest.php
│       │               ├── CrossSellDataProviderTest.php
│       │               ├── RelatedDataProviderTest.php
│       │               └── UpSellDataProviderTest.php
│       ├── ViewModel
│       │   └── Product
│       │       ├── BreadcrumbsTest.php
│       │       └── Checker
│       │           └── AddToCompareAvailabilityTest.php
│       └── _files
│           └── catalog
│               └── product
│                   ├── somefile.png
│                   └── watermark
│                       └── somefile.png
├── Ui
│   ├── AllowedProductTypes.php
│   ├── Component
│   │   ├── Category
│   │   │   └── Form
│   │   │       └── Element
│   │   │           └── Wysiwyg.php
│   │   ├── ColumnFactory.php
│   │   ├── FilterFactory.php
│   │   ├── Listing
│   │   │   ├── Attribute
│   │   │   │   ├── AbstractRepository.php
│   │   │   │   ├── Repository.php
│   │   │   │   └── RepositoryInterface.php
│   │   │   ├── Columns
│   │   │   │   ├── AttributeSetId.php
│   │   │   │   ├── AttributeSetText.php
│   │   │   │   ├── Price.php
│   │   │   │   ├── ProductActions.php
│   │   │   │   ├── StatusText.php
│   │   │   │   ├── Thumbnail.php
│   │   │   │   └── Websites.php
│   │   │   ├── Columns.php
│   │   │   └── Filters.php
│   │   ├── Product
│   │   │   ├── Form
│   │   │   │   └── Categories
│   │   │   │       └── Options.php
│   │   │   └── MassAction.php
│   │   └── UrlInput
│   │       ├── Category.php
│   │       └── Product.php
│   └── DataProvider
│       ├── CatalogEavValidationRules.php
│       └── Product
│           ├── AddSearchKeyConditionToCollection.php
│           ├── AddStoreFieldToCollection.php
│           ├── AddWebsitesFieldToCollection.php
│           ├── Attributes
│           │   └── Listing.php
│           ├── Form
│           │   ├── Modifier
│           │   │   ├── AbstractModifier.php
│           │   │   ├── AdvancedPricing.php
│           │   │   ├── Alerts.php
│           │   │   ├── AttributeSet.php
│           │   │   ├── Attributes.php
│           │   │   ├── Categories.php
│           │   │   ├── CurrencySymbolProvider.php
│           │   │   ├── CustomOptions.php
│           │   │   ├── Eav
│           │   │   │   ├── CompositeConfigProcessor.php
│           │   │   │   ├── WysiwygConfigDataProcessor.php
│           │   │   │   └── WysiwygConfigDataProcessorInterface.php
│           │   │   ├── Eav.php
│           │   │   ├── General.php
│           │   │   ├── Images.php
│           │   │   ├── LayoutUpdate.php
│           │   │   ├── Related.php
│           │   │   ├── ScheduleDesignUpdate.php
│           │   │   ├── System.php
│           │   │   ├── TierPrice.php
│           │   │   └── Websites.php
│           │   ├── NewCategoryDataProvider.php
│           │   └── ProductDataProvider.php
│           ├── Listing
│           │   ├── Collector
│           │   │   ├── AdditionalInfo.php
│           │   │   ├── Image.php
│           │   │   ├── Price.php
│           │   │   └── Url.php
│           │   └── DataProvider.php
│           ├── Modifier
│           │   ├── Attributes.php
│           │   └── PriceAttributes.php
│           ├── ProductCollection.php
│           ├── ProductCustomOptionsDataProvider.php
│           ├── ProductDataProvider.php
│           ├── ProductRenderCollectorComposite.php
│           ├── ProductRenderCollectorInterface.php
│           └── Related
│               ├── AbstractDataProvider.php
│               ├── CrossSellDataProvider.php
│               ├── RelatedDataProvider.php
│               └── UpSellDataProvider.php
├── ViewModel
│   ├── Category
│   │   ├── Image.php
│   │   └── Output.php
│   └── Product
│       ├── Breadcrumbs.php
│       ├── Checker
│       │   └── AddToCompareAvailability.php
│       ├── Listing
│       │   └── PreparePostData.php
│       └── OptionsData.php
├── composer.json
├── etc
│   ├── acl.xml
│   ├── adminhtml
│   │   ├── di.xml
│   │   ├── events.xml
│   │   ├── menu.xml
│   │   ├── routes.xml
│   │   └── system.xml
│   ├── catalog_attributes.xml
│   ├── catalog_attributes.xsd
│   ├── communication.xml
│   ├── config.xml
│   ├── crontab.xml
│   ├── db_schema.xml
│   ├── db_schema_whitelist.json
│   ├── di.xml
│   ├── eav_attributes.xml
│   ├── events.xml
│   ├── extension_attributes.xml
│   ├── frontend
│   │   ├── di.xml
│   │   ├── events.xml
│   │   ├── page_types.xml
│   │   ├── routes.xml
│   │   └── sections.xml
│   ├── indexer.xml
│   ├── module.xml
│   ├── mview.xml
│   ├── product_options.xml
│   ├── product_options.xsd
│   ├── product_options_merged.xsd
│   ├── product_types.xml
│   ├── product_types.xsd
│   ├── product_types_base.xsd
│   ├── product_types_merged.xsd
│   ├── queue.xml
│   ├── queue_consumer.xml
│   ├── queue_publisher.xml
│   ├── queue_topology.xml
│   ├── view.xml
│   ├── webapi.xml
│   ├── webapi_async.xml
│   ├── webapi_rest
│   │   └── di.xml
│   ├── webapi_soap
│   │   └── di.xml
│   └── widget.xml
├── i18n
│   └── en_US.csv
├── registration.php
├── tree_output.txt
└── view
    ├── adminhtml
    │   ├── layout
    │   │   ├── CATALOG_PRODUCT_COMPOSITE_CONFIGURE.xml
    │   │   ├── CATALOG_PRODUCT_COMPOSITE_CONFIGURE_ERROR.xml
    │   │   ├── CATALOG_PRODUCT_COMPOSITE_UPDATE_RESULT.xml
    │   │   ├── catalog_category_add.xml
    │   │   ├── catalog_category_create.xml
    │   │   ├── catalog_category_edit.xml
    │   │   ├── catalog_product_action_attribute_edit.xml
    │   │   ├── catalog_product_alertspricegrid.xml
    │   │   ├── catalog_product_alertsstockgrid.xml
    │   │   ├── catalog_product_attribute_edit.xml
    │   │   ├── catalog_product_attribute_edit_form.xml
    │   │   ├── catalog_product_attribute_edit_popup.xml
    │   │   ├── catalog_product_change_attribute_set.xml
    │   │   ├── catalog_product_crosssell.xml
    │   │   ├── catalog_product_crosssellgrid.xml
    │   │   ├── catalog_product_customoptions.xml
    │   │   ├── catalog_product_edit.xml
    │   │   ├── catalog_product_form.xml
    │   │   ├── catalog_product_grid.xml
    │   │   ├── catalog_product_index.xml
    │   │   ├── catalog_product_new.xml
    │   │   ├── catalog_product_options.xml
    │   │   ├── catalog_product_optionsimportgrid.xml
    │   │   ├── catalog_product_related.xml
    │   │   ├── catalog_product_relatedgrid.xml
    │   │   ├── catalog_product_reload.xml
    │   │   ├── catalog_product_set_block.xml
    │   │   ├── catalog_product_set_edit.xml
    │   │   ├── catalog_product_set_index.xml
    │   │   ├── catalog_product_upsell.xml
    │   │   └── catalog_product_upsellgrid.xml
    │   ├── requirejs-config.js
    │   ├── templates
    │   │   ├── catalog
    │   │   │   ├── category
    │   │   │   │   ├── checkboxes
    │   │   │   │   │   └── tree.phtml
    │   │   │   │   ├── edit
    │   │   │   │   │   └── assign_products.phtml
    │   │   │   │   ├── edit.phtml
    │   │   │   │   ├── tree.phtml
    │   │   │   │   └── widget
    │   │   │   │       └── tree.phtml
    │   │   │   ├── form
    │   │   │   │   └── renderer
    │   │   │   │       └── fieldset
    │   │   │   │           └── element.phtml
    │   │   │   ├── product
    │   │   │   │   ├── attribute
    │   │   │   │   │   ├── form.phtml
    │   │   │   │   │   ├── js.phtml
    │   │   │   │   │   ├── labels.phtml
    │   │   │   │   │   ├── options.phtml
    │   │   │   │   │   └── set
    │   │   │   │   │       ├── main
    │   │   │   │   │       │   └── tree
    │   │   │   │   │       │       ├── attribute.phtml
    │   │   │   │   │       │       └── group.phtml
    │   │   │   │   │       ├── main.phtml
    │   │   │   │   │       └── toolbar
    │   │   │   │   │           ├── add.phtml
    │   │   │   │   │           └── main.phtml
    │   │   │   │   ├── composite
    │   │   │   │   │   ├── configure.phtml
    │   │   │   │   │   └── fieldset
    │   │   │   │   │       ├── options
    │   │   │   │   │       │   ├── js.phtml
    │   │   │   │   │       │   └── type
    │   │   │   │   │       │       ├── date.phtml
    │   │   │   │   │       │       ├── default.phtml
    │   │   │   │   │       │       ├── file.phtml
    │   │   │   │   │       │       ├── select.phtml
    │   │   │   │   │       │       └── text.phtml
    │   │   │   │   │       ├── options.phtml
    │   │   │   │   │       └── qty.phtml
    │   │   │   │   ├── edit
    │   │   │   │   │   ├── action
    │   │   │   │   │   │   ├── attribute.phtml
    │   │   │   │   │   │   ├── inventory.phtml
    │   │   │   │   │   │   └── websites.phtml
    │   │   │   │   │   ├── attribute_set.phtml
    │   │   │   │   │   ├── category
    │   │   │   │   │   │   └── new
    │   │   │   │   │   │       └── form.phtml
    │   │   │   │   │   ├── options
    │   │   │   │   │   │   ├── option.phtml
    │   │   │   │   │   │   └── type
    │   │   │   │   │   │       ├── date.phtml
    │   │   │   │   │   │       ├── file.phtml
    │   │   │   │   │   │       ├── select.phtml
    │   │   │   │   │   │       └── text.phtml
    │   │   │   │   │   ├── options.phtml
    │   │   │   │   │   ├── price
    │   │   │   │   │   │   └── tier.phtml
    │   │   │   │   │   ├── serializer.phtml
    │   │   │   │   │   └── websites.phtml
    │   │   │   │   ├── edit.phtml
    │   │   │   │   ├── helper
    │   │   │   │   │   └── gallery.phtml
    │   │   │   │   ├── js.phtml
    │   │   │   │   ├── tab
    │   │   │   │   │   ├── alert.phtml
    │   │   │   │   │   └── inventory.phtml
    │   │   │   │   └── widget
    │   │   │   │       └── chooser
    │   │   │   │           └── container.phtml
    │   │   │   └── product.phtml
    │   │   ├── product
    │   │   │   ├── edit
    │   │   │   │   ├── attribute
    │   │   │   │   │   └── search.phtml
    │   │   │   │   ├── tabs
    │   │   │   │   │   └── child_tab.phtml
    │   │   │   │   └── tabs.phtml
    │   │   │   └── grid
    │   │   │       ├── massaction_extended.phtml
    │   │   │       └── url_filter_applier.phtml
    │   │   └── rss
    │   │       └── grid
    │   │           └── link.phtml
    │   ├── ui_component
    │   │   ├── category_form.xml
    │   │   ├── crosssell_product_listing.xml
    │   │   ├── design_config_form.xml
    │   │   ├── new_category_form.xml
    │   │   ├── product_attribute_add_form.xml
    │   │   ├── product_attributes_grid.xml
    │   │   ├── product_custom_options_listing.xml
    │   │   ├── product_form.xml
    │   │   ├── product_listing.xml
    │   │   ├── related_product_listing.xml
    │   │   └── upsell_product_listing.xml
    │   └── web
    │       ├── catalog
    │       │   ├── apply-to-type-switcher.js
    │       │   ├── base-image-uploader.js
    │       │   ├── category
    │       │   │   ├── assign-products.js
    │       │   │   └── form.js
    │       │   ├── images
    │       │   │   ├── select2.png
    │       │   │   ├── select2x2.png
    │       │   │   └── spinner.gif
    │       │   ├── product
    │       │   │   ├── attribute
    │       │   │   │   └── unique-validate.js
    │       │   │   ├── composite
    │       │   │   │   └── configure.js
    │       │   │   └── edit
    │       │   │       └── attribute.js
    │       │   ├── product-attributes.js
    │       │   ├── product.js
    │       │   └── type-events.js
    │       ├── component
    │       │   ├── file-type-field.js
    │       │   ├── image-size-field.js
    │       │   ├── select-type-grid.js
    │       │   ├── static-type-container.js
    │       │   ├── static-type-input.js
    │       │   ├── static-type-select.js
    │       │   └── text-type-field.js
    │       ├── images
    │       │   ├── ajax-loader-big.gif
    │       │   ├── category_widget_link.png
    │       │   ├── product_widget_link.png
    │       │   ├── product_widget_new.png
    │       │   └── product_widget_viewed.png
    │       ├── js
    │       │   ├── bundle-proxy-button.js
    │       │   ├── category-checkbox-tree.js
    │       │   ├── category-tree.js
    │       │   ├── components
    │       │   │   ├── attribute-set-select.js
    │       │   │   ├── attributes-fieldset.js
    │       │   │   ├── attributes-grid-paging.js
    │       │   │   ├── attributes-insert-listing.js
    │       │   │   ├── checkbox.js
    │       │   │   ├── custom-options-component.js
    │       │   │   ├── custom-options-price-type.js
    │       │   │   ├── disable-hide-select.js
    │       │   │   ├── disable-on-option
    │       │   │   │   ├── input.js
    │       │   │   │   ├── select.js
    │       │   │   │   ├── strategy.js
    │       │   │   │   └── yesno.js
    │       │   │   ├── dynamic-rows-import-custom-options-per-page.js
    │       │   │   ├── dynamic-rows-import-custom-options.js
    │       │   │   ├── dynamic-rows-per-page.js
    │       │   │   ├── dynamic-rows-tier-price.js
    │       │   │   ├── import-handler.js
    │       │   │   ├── messages.js
    │       │   │   ├── new-attribute-form.js
    │       │   │   ├── new-attribute-insert-form.js
    │       │   │   ├── new-category.js
    │       │   │   ├── product-ui-select.js
    │       │   │   ├── reset-dynamic-rows-grid-row-position-on-delete.js
    │       │   │   ├── url-key-handle-changes.js
    │       │   │   ├── use-parent-settings
    │       │   │   │   ├── select.js
    │       │   │   │   ├── single-checkbox.js
    │       │   │   │   ├── textarea.js
    │       │   │   │   └── toggle-disabled-mixin.js
    │       │   │   ├── visible-on-option
    │       │   │   │   ├── date.js
    │       │   │   │   ├── fieldset.js
    │       │   │   │   ├── input.js
    │       │   │   │   ├── select.js
    │       │   │   │   ├── strategy.js
    │       │   │   │   ├── textarea.js
    │       │   │   │   └── yesno.js
    │       │   │   └── website-currency-symbol.js
    │       │   ├── custom-options-type.js
    │       │   ├── custom-options.js
    │       │   ├── edit-tree.js
    │       │   ├── form
    │       │   │   └── element
    │       │   │       ├── action-delete.js
    │       │   │       ├── checkbox.js
    │       │   │       └── input.js
    │       │   ├── new-category-dialog.js
    │       │   ├── options.js
    │       │   ├── product
    │       │   │   └── weight-handler.js
    │       │   ├── product-gallery.js
    │       │   ├── tier-price
    │       │   │   ├── percentage-processor.js
    │       │   │   └── value-type-select.js
    │       │   └── utils
    │       │       └── percentage-price-calculator.js
    │       ├── product
    │       │   └── images
    │       │       ├── ui-bg_diagonals-thick_18_b81900_40x40.png
    │       │       ├── ui-bg_diagonals-thick_20_666666_40x40.png
    │       │       ├── ui-bg_flat_10_000000_40x100.png
    │       │       ├── ui-bg_glass_100_f6f6f6_1x400.png
    │       │       ├── ui-bg_glass_100_fdf5ce_1x400.png
    │       │       ├── ui-bg_glass_65_ffffff_1x400.png
    │       │       ├── ui-bg_gloss-wave_35_f67028_500x100.png
    │       │       ├── ui-bg_highlight-soft_100_eeeeee_1x100.png
    │       │       ├── ui-bg_highlight-soft_75_ffe45c_1x100.png
    │       │       ├── ui-icons_222222_256x240.png
    │       │       ├── ui-icons_228ef1_256x240.png
    │       │       ├── ui-icons_ef8c08_256x240.png
    │       │       ├── ui-icons_ffd27a_256x240.png
    │       │       └── ui-icons_ffffff_256x240.png
    │       └── template
    │           ├── attributes
    │           │   └── grid
    │           │       └── paging.html
    │           ├── checkbox.html
    │           ├── components
    │           │   ├── dynamic-rows-import-custom-options-per-page.html
    │           │   └── dynamic-rows-per-page.html
    │           ├── form
    │           │   ├── element
    │           │   │   ├── action-delete.html
    │           │   │   ├── checkbox.html
    │           │   │   ├── frontend-input-select.html
    │           │   │   ├── helper
    │           │   │   │   ├── custom-option-service.html
    │           │   │   │   └── custom-option-type-service.html
    │           │   │   └── input.html
    │           │   └── field.html
    │           ├── grid
    │           │   └── cells
    │           │       └── preserved.html
    │           └── image-preview.html
    ├── base
    │   ├── layout
    │   │   ├── catalog_product_prices.xml
    │   │   ├── default.xml
    │   │   └── empty.xml
    │   ├── requirejs-config.js
    │   ├── templates
    │   │   ├── js
    │   │   │   └── components.phtml
    │   │   └── product
    │   │       ├── composite
    │   │       │   └── fieldset
    │   │       │       └── options
    │   │       │           └── view
    │   │       │               └── checkable.phtml
    │   │       └── price
    │   │           ├── amount
    │   │           │   └── default.phtml
    │   │           ├── configured_price.phtml
    │   │           ├── default.phtml
    │   │           ├── final_price.phtml
    │   │           └── tier_prices.phtml
    │   └── web
    │       ├── images
    │       │   ├── category
    │       │   │   └── placeholder
    │       │   │       └── image.jpg
    │       │   └── product
    │       │       └── placeholder
    │       │           ├── image.jpg
    │       │           ├── small_image.jpg
    │       │           ├── swatch_image.jpg
    │       │           └── thumbnail.jpg
    │       ├── js
    │       │   ├── price-box.js
    │       │   ├── price-option-date.js
    │       │   ├── price-option-file.js
    │       │   ├── price-options.js
    │       │   ├── price-utils.js
    │       │   └── product
    │       │       ├── addtocart-button.js
    │       │       ├── addtocompare-button.js
    │       │       ├── learn-more.js
    │       │       ├── list
    │       │       │   ├── column-status-validator.js
    │       │       │   ├── columns
    │       │       │   │   ├── final-price.js
    │       │       │   │   ├── image.js
    │       │       │   │   ├── price-box.js
    │       │       │   │   └── pricetype-box.js
    │       │       │   └── listing.js
    │       │       └── name.js
    │       └── template
    │           └── product
    │               ├── final_price.html
    │               ├── link.html
    │               ├── list
    │               │   ├── columns
    │               │   │   ├── image.html
    │               │   │   └── image_with_borders.html
    │               │   └── listing.html
    │               ├── name.html
    │               └── price
    │                   ├── max_price.html
    │                   ├── max_regular_price.html
    │                   ├── minimal_price.html
    │                   ├── minimal_regular_price.html
    │                   ├── price_box.html
    │                   ├── pricetype_box.html
    │                   ├── regular_price.html
    │                   └── special_price.html
    └── frontend
        ├── layout
        │   ├── catalog_category_view.xml
        │   ├── catalog_category_view_type_default.xml
        │   ├── catalog_category_view_type_default_without_children.xml
        │   ├── catalog_product_compare_index.xml
        │   ├── catalog_product_gallery.xml
        │   ├── catalog_product_opengraph.xml
        │   ├── catalog_product_view.xml
        │   ├── catalog_product_view_type_simple.xml
        │   ├── catalog_product_view_type_virtual.xml
        │   ├── checkout_cart_item_renderers.xml
        │   └── default.xml
        ├── requirejs-config.js
        ├── templates
        │   ├── category
        │   │   ├── cms.phtml
        │   │   ├── description.phtml
        │   │   ├── image.phtml
        │   │   ├── products.phtml
        │   │   ├── rss.phtml
        │   │   └── widget
        │   │       └── link
        │   │           ├── link_block.phtml
        │   │           ├── link_href.phtml
        │   │           └── link_inline.phtml
        │   ├── frontend_storage_manager.phtml
        │   ├── messages
        │   │   └── addCompareSuccessMessage.phtml
        │   ├── navigation
        │   │   └── left.phtml
        │   └── product
        │       ├── breadcrumbs.phtml
        │       ├── compare
        │       │   ├── link.phtml
        │       │   ├── list.phtml
        │       │   └── sidebar.phtml
        │       ├── gallery.phtml
        │       ├── image.phtml
        │       ├── image_with_borders.phtml
        │       ├── list
        │       │   ├── addto
        │       │   │   └── compare.phtml
        │       │   ├── items.phtml
        │       │   ├── toolbar
        │       │   │   ├── amount.phtml
        │       │   │   ├── limiter.phtml
        │       │   │   ├── sorter.phtml
        │       │   │   └── viewmode.phtml
        │       │   └── toolbar.phtml
        │       ├── list.phtml
        │       ├── listing.phtml
        │       ├── view
        │       │   ├── additional.phtml
        │       │   ├── addto
        │       │   │   └── compare.phtml
        │       │   ├── addto.phtml
        │       │   ├── addtocart.phtml
        │       │   ├── attribute.phtml
        │       │   ├── attributes.phtml
        │       │   ├── counter.phtml
        │       │   ├── description.phtml
        │       │   ├── details.phtml
        │       │   ├── form.phtml
        │       │   ├── gallery.phtml
        │       │   ├── mailto.phtml
        │       │   ├── opengraph
        │       │   │   ├── currency.phtml
        │       │   │   └── general.phtml
        │       │   ├── options
        │       │   │   ├── type
        │       │   │   │   ├── date.phtml
        │       │   │   │   ├── default.phtml
        │       │   │   │   ├── file.phtml
        │       │   │   │   ├── select.phtml
        │       │   │   │   └── text.phtml
        │       │   │   ├── wrapper
        │       │   │   │   └── bottom.phtml
        │       │   │   └── wrapper.phtml
        │       │   ├── options.phtml
        │       │   ├── price_clone.phtml
        │       │   ├── review.phtml
        │       │   └── type
        │       │       └── default.phtml
        │       └── widget
        │           ├── compared
        │           │   ├── grid.phtml
        │           │   ├── list.phtml
        │           │   └── sidebar.phtml
        │           ├── link
        │           │   ├── link_block.phtml
        │           │   └── link_inline.phtml
        │           ├── new
        │           │   ├── column
        │           │   │   ├── new_default_list.phtml
        │           │   │   ├── new_images_list.phtml
        │           │   │   └── new_names_list.phtml
        │           │   └── content
        │           │       ├── new_grid.phtml
        │           │       └── new_list.phtml
        │           └── viewed
        │               ├── grid.phtml
        │               ├── list.phtml
        │               └── sidebar.phtml
        ├── ui_component
        │   ├── widget_recently_compared.xml
        │   └── widget_recently_viewed.xml
        └── web
            ├── images
            │   ├── product_widget_compared.gif
            │   └── product_widget_viewed.gif
            ├── js
            │   ├── catalog-add-to-cart.js
            │   ├── gallery.js
            │   ├── list.js
            │   ├── product
            │   │   ├── breadcrumbs.js
            │   │   ├── list
            │   │   │   └── toolbar.js
            │   │   ├── provider-compared.js
            │   │   ├── provider.js
            │   │   ├── query-builder.js
            │   │   ├── remaining-characters.js
            │   │   ├── storage
            │   │   │   ├── data-storage.js
            │   │   │   ├── ids-storage-compare.js
            │   │   │   ├── ids-storage.js
            │   │   │   └── storage-service.js
            │   │   ├── uenc-processor.js
            │   │   └── view
            │   │       ├── product-ids-resolver.js
            │   │       ├── product-ids.js
            │   │       ├── product-info-resolver.js
            │   │       ├── product-info.js
            │   │       └── provider.js
            │   ├── related-products.js
            │   ├── storage-manager.js
            │   ├── upsell-products.js
            │   ├── validate-product.js
            │   └── view
            │       ├── compare-products.js
            │       └── image.js
            ├── product
            │   └── view
            │       └── validation.js
            └── template
                └── product
                    ├── addtocart-button.html
                    ├── addtocompare-button.html
                    ├── image.html
                    └── image_with_borders.html
```

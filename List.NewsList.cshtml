@model Telerik.Sitefinity.Frontend.DynamicContent.Mvc.Models.DynamicContentListViewModel

@using Telerik.Sitefinity.Frontend.DynamicContent.WidgetTemplates.Fields.Helpers;
@using Telerik.Sitefinity;
@using Telerik.Sitefinity.Data.ContentLinks;
@using Telerik.Sitefinity.Frontend.Mvc.Helpers;
@using Telerik.Sitefinity.Frontend.DynamicContent.Mvc.Helpers;
@using Telerik.Sitefinity.Frontend.Mvc.Models;
@using Telerik.Sitefinity.Web.DataResolving;
@using Telerik.Sitefinity.Model.ContentLinks;
@using Telerik.Sitefinity.Modules.Pages;

<div class="@Model.CssClass">
	<ul class="ig_news">
		@foreach (var item in Model.Items)
		{
			var navigateUrl = HyperLinkHelpers.GetDetailPageUrl(item, ViewBag.DetailsPageId, ViewBag.OpenInSamePage, Model.UrlKeyPrefix);
			<li @Html.InlineEditingAttributes(Model.ProviderName, Model.ContentType.FullName, (Guid)item.Fields.Id)>
				<h3>
					<a href="@navigateUrl">
						@item.Fields.Title
					</a>
				</h3>
				<div>@item.ParentItem().Fields.Title</div>
				@{
					List<ItemViewModel> IgLeaders = new List<ItemViewModel>(@item.ParentItem().Fields.InterestGroupLeaders);
					IgLeaders.Sort((a, b) => a.Fields.LastName.CompareTo(b.Fields.LastName));

					List<ItemViewModel> IgNewsPanelists = new List<ItemViewModel>(@item.Fields.Panelists);
					IgNewsPanelists.Sort((a, b) => a.Fields.LastName.CompareTo(b.Fields.LastName));
				}
				<ul>
					@foreach (var IgLeader in IgLeaders)
					{
						<li>@IgLeader.Fields.Title</li>
					}
				</ul>
				<small>@item.GetDateTime("PublicationDate", "MMM d, yyyy, HH:mm tt")</small>
				<h6>Panelists</h6>
				<ul>
					@foreach (var IgNewsPanelist in IgNewsPanelists)
					{
						<li>@IgNewsPanelist.Fields.Title</li>
					}
				</ul>
				@Html.HtmlSanitize((string)item.Fields.AgendaTopics)
			</li>
		}
	</ul>
</div>

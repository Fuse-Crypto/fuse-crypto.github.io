---
layout: default
title: test
---

# Tests
<pre>
page.path: {{ page.path}} 
page.name: {{ page.name }} 
page.url: {{ page.url }} 
page: {{ page | jsonify | escape }} 

site.github.repository_url        : {{ site.github.repository_url }} 
site.github.api_url               : {{ site.github.api_url }} 
site.github.archived              : {{ site.github.archived }} 
site.github.baseurl               : {{ site.github.baseurl }} 
site.github.build_revision        : {{ site.github.build_revision }} 
site.github.clone_url             : {{ site.github.clone_url }} 
site.github.contributors          : {{ site.github.contributors }} 
site.github.disabled              : {{ site.github.disabled }} 
site.github.environment           : {{ site.github.environment }} 
site.github.help_url              : {{ site.github.help_url }} 
site.github.hostname              : {{ site.github.hostname }} 
site.github.is_project_page       : {{ site.github.is_project_page }} 
site.github.is_user_page          : {{ site.github.is_user_page }} 
site.github.issues_url            : {{ site.github.issues_url }} 
site.github.language              : {{ site.github.language }} 
site.github.latest_release        : {{ site.github.latest_release }} 
site.github.license               : {{ site.github.license }} 
site.github.organization_members  : {{ site.github.organization_members }} 
site.github.owner                 : {{ site.github.owner }} 
site.github.owner_gravatar_url    : {{ site.github.owner_gravatar_url }} 
site.github.owner_name            : {{ site.github.owner_name }} 
site.github.owner_url             : {{ site.github.owner_url }} 
site.github.pages_env             : {{ site.github.pages_env }} 
site.github.pages_hostname        : {{ site.github.pages_hostname }} 
site.github.private               : {{ site.github.private }} 
site.github.project_tagline       : {{ site.github.project_tagline }} 
site.github.project_title         : {{ site.github.project_title }} 
site.github.public_repositories   : {{ site.github.public_repositories }} 
site.github.releases              : {{ site.github.release }} 
site.github.releases_url          : {{ site.github.releases_url }} 
site.github.repository_name       : {{ site.github.repository_name  }} 
site.github.repository_nwo        : {{ site.github.repository_nwo }} 
site.github.repository_url        : {{ site.github.repository_url }} 
site.github.show_downloads        : {{ site.github.show_downloads }} 
site.github.source                : {{ site.github.source  }} 
site.github.tar_url               : {{ site.github.tar_url  }} 
site.github.versions              : {{ site.github.versions }} 
site.github.wiki_url              : {{ site.github.wiki_url }} 
site.github.zip_url               : {{ site.github.zip_url }} 

site.github: {{ site.github | jsonify | escape }} 

site: {{ site | jsonify | escape }} 
</pre>

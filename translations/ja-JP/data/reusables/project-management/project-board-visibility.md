By default, user-owned and organization-wide project boards are private and only visible to people with read, write, or admin permissions to the project board. {% ifversion ghae %}インターナル{% else %}パブリック{% endif %}プロジェクトボードは、プロジェクトボードのURLを知っていれば{% ifversion ghae %}Enterpriseのメンバーは誰でも{% else %}誰でも{% endif %}見ることができます。 Repository-level project boards share the visibility of their repository. That is, a private repository will have a private board, and this visibility cannot be changed.
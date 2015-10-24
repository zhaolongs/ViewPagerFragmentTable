# ViewPagerFragmentTable
examlpe

public class CopyNewsFragment extends BaseViewPagerFragment {
    @Override
    protected void onSetupTabAdapter(ViewPageFragmentAdapter adapter) {

        /**
         * public void addTab(String title, String tag, Class<?> clss, Bundle args)
         */
        adapter.addTab("test1","12",NewsInformationFragment.class,null);
        adapter.addTab("test2","12",HotSpotFragment.class,null);
        adapter.addTab("test3","12",BologFragment.class,null);
        adapter.addTab("test4","12",RecommendFragment.class,null);

    }
}

NewsInformationFragment,HotSpotFragment,BologFragment,RecommendFragment
分别继承于fragment

在MainActivity中进行调用CopyNewsFragment

